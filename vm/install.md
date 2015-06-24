---
layout: page
title: Installing the HMT VM
---




## Prerequisites ##

The HMT VM uses Vagrant to define a virtual machine you can run with  VirtualBox.  The two prerequisites for running `vm2015` are therefore:

- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)
- 

## Getting started ##

The  github repository for the VM is <https://github.com/homermultitext/vm2015.git>.  Clone or download a copy of the repository.  From a terminal within the `vm2015` directory, run

    vagrant up

> Your machine must be able to run a 64-bit VM.  Some computers have BIOS settings that prohibit this.  If that happens, you will have to change your BIOS settings to allow the 64-bit VM to run.





To install the full suite of tools for HMT project editing, run

    refresh-hmt.sh



## Trouble shooting ##

