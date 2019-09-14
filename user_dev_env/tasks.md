* Create a server based on Centos:
  * create users: prod, test, beta
  * every user and every future user needs to have Bello.sh script embedded in their home directory and should every time they connect.
  * every user and future user must have these folders in their home directory: Project/{shell,python,groovy,ruby}
  * the server needs to have these environments on demand:
    * fish - interactive bash shell environment.
    * ipython - interactive python shell.
    * irb - interactive ruby shell
    * groovysh - interactive groovy shell.

* the server must have git tool installed and set up with remote server(it can be your server.)
* future users should have git setup as part of their creation.
* create additional storage disks and set them up as LVM.
