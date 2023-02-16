## Lab 2

* Create public-private key pair and add  the public key to the server
  * ssh-keygen
* Add password for root account for disaster recovery
  * sudo su
  * passwd root
* Add user
  * sudo adduser scoring
  * su scoring
  * cd ~
* Add ssh key
  * mkdir .ssh
  * chown scoring:scoring .ssh
  * chmod 700 .ssh
  * cd .ssh
  * wget https://scoring.sa.cs.ut.ee/files/id_rsa.pub
  * cat id_rsa.pub >> authorized_keys
  * rm id_rsa.pub
  * chmod 600 authorized_keys
* Give scoring user root permissions
  * su -
  * sudo visudo
  * add line `scoring ALL=(ALL:ALL) NOPASSWD: ALL`
