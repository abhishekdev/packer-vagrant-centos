# packer-vagrant-centos

[Packer.io](http://packer.io) template for CentOS box with puppet

- CentOS 6.8 (Minimal) 64-bit + puppet

## Use

Use hosted VirtualBox image

```shell
vagrant init abhishekdev/centos-6-x64-puppet; vagrant up --provider virtualbox
```

## Build

- Install packer from <http://packer.io>
- Run `packer build centos-6-x64.json` from the project root
- Use the box (generated in `build` subdirectory) with [Vagrant](http://vagrantup.com) and [VirtualBox](http://virtualbox.org).

## Credits

[packer-vagrant-linux](https://bitbucket.org/ariya/packer-vagrant-linux) by Ariya Hidayat
