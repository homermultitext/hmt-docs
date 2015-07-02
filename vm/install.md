---
layout: page
title: Installing the HMT VM
---




## Prerequisites ##

The HMT VM uses Vagrant to define a virtual machine you can run with  VirtualBox.  The two prerequisites for running `vm2015` are therefore:

- [Vagrant](https://www.vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)




## Getting started ##

In the course of building the VM, your computer will download a load of material, so make sure you have a good internet connection.  Start by opening a terminal session, and change directories to where you want to install the virtual machine (e.g. to go to your desktop: `cd Desktop`).  

The  github repository for the VM is <https://github.com/homermultitext/vm2015.git>.  Clone it with normal git command:

    git clone https://github.com/homermultitext/vm2015.git

Change directories to the newly cloned VM (`cd vm2015`), and from within the `vm2015` directory, run

    vagrant up

> Your machine must be able to run a 64-bit VM.  Some computers have BIOS settings that prohibit this.  If that happens, you will have to change your BIOS settings to allow the 64-bit VM to run.


This is the routine command to start the virtual machine: since this is first time you have run it, vagrant will proceed to build the VM from scratch.

Find something to occupy yourself for awhile, but don't let your computer go to sleep before the build has completely finished:  vagrant is not always able to resume cleanly if the process is interrupted.  (Don’t forget and do something silly like shut your laptop. It has happened.)

A new window with a login screen will eventually pop up.  Don't log in until the entire build process has completed in your original terminal session on your host computer, however.

When the build is complete, log in to the VM from the new window. The username and password are both `vagrant`.



## Installing the HMT editorial system ##

First, follow these instructions to [install one more keyboard layouts](../keyboard) that you are comfortable using.
From the start menu at the bottom left of the screen, you can open a terminal running a bash shell.  Choose LXTerminal from the Accessories menu.


![LX Terminal](../imgs/lxterm.png)

To install the full suite of tools for HMT project editing, run

    refresh-hmt.sh


When you are done , you can shut down the virtual machine from your original terminal session on your host computer by running

    vagrant halt

You will want to remember to do this because otherwise the machine will keep running and draining your battery.


## Trouble shooting ##






