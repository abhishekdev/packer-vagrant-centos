packer-vagrant-centos
=====================

[Packer.io](http://packer.io) template for CentOS box with puppet
* CentOS 6.5 (Minimal) 64-bit + puppet

# Instructions
- Install packer from [http://packer.io](http://packer.io)
- Run `packer build centos-6.5-x64.json` from the project root
- Use the box (generated in `build` subdirectory) with [Vagrant](http://vagrantup.com) and [VirtualBox](http://virtualbox.org).

###Credits:
[packer-vagrant-linux](https://bitbucket.org/ariya/packer-vagrant-linux) by Ariya Hidayat
