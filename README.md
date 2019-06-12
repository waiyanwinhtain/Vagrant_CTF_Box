# Vagrant vm for CTF competitions

## What is this?

This is a ubuntu-based vagrant vm for CTF competitions with some helpful tools included.

## Installation

Download vagrant file and make directory ~/Documents/ctf/2019
`❯ curl https://raw.githubusercontent.com/tcode2k16/vagrant_vm/master/ubuntu_ctf/Vagrantfile > Vagrantfile`

Run the installation process (*This will take around 1 hour if it is the first time you run this*)

`❯ vagrant up`

Access the vm

`> vagrant ssh`

Shutdown the vm

`> vagrant halt`

## Tools included

* x86 binary libs
* gdb with gef
* binwalk
* exiftool
* imagemagick
* nmap
* socat
* unzip
* python2
* ruby
* radare2 with r2dec
* libc-database
* pwntools
* one_gadget
* angr
* frida
* ipython
* masscan
* featherduster
* sqlmap

