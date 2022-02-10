# ocm-backplane-container
How to install and use the ocm-backplane-container tool


The first step is to clone the [openshift/ocm-container repository](https://github.com/openshift/ocm-container) into the local machine:

~~~
$ git clone https://github.com/openshift/ocm-container.git
Cloning into 'ocm-container'...
remote: Enumerating objects: 998, done.
remote: Counting objects: 100% (242/242), done.
remote: Compressing objects: 100% (88/88), done.
remote: Total 998 (delta 199), reused 164 (delta 154), pack-reused 756
Receiving objects: 100% (998/998), 221.78 KiB | 2.46 MiB/s, done.
Resolving deltas: 100% (552/552), done.

~~~

Run the `./init.sh` script in the `ocm-container/` folder that has been created at the cloning step, it will ask the root password for the machine:

~~~
$ ./init.sh
ocm-container is already configured.
Creating symlink for ocm-container binary (requires sudo permissions...)
[sudo] password for <UserName>: 

Tip: Many developers like to add the following alias:
alias ocm-container-stg="OCM_URL=staging ocm-container"


ocm-container configuration can be customized by editing /home/UserName/.config/ocm-container/env.source

~~~

Then, lunch the `./build.sh` script on the same folder than the last script, this takes a long time:

~~~

~~~
