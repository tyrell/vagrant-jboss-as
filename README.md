Vagrant JBoss 7.1.x
======================

This is the simple vagrant setup installing Java 7 and JBoss 7.1.x on Ubuntu Precise 64

## How to Start

1. Install [VirtualBox](https://www.virtualbox.org/)
2. Install [Vagrant](http://www.vagrantup.com/)
3. Startup Vagrant by executing `vagrant up`
4. Connect to the server by executing `vagrant ssh`

## Notes
- The operating system provisioned in the new VM created is Ubuntu Server 14.04 LTS (Trusty Tahr).
- The Java version installed is Java 7.
- JBoss is installed to `/opt/jboss-as` directory, and it is run with `jboss-as` user's permissions.
- A private network is created, with an IP address equal to `192.168.56.128`. 
- JBoss is accessible under `http://192.168.56.128:8080`.
- VIM, Subversion and HTOP are installed as utilities.
