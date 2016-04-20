---
title:  "HMT editors' virtual machine"
layout: page
---



The HMT project VM for editors is a virtual machine including all the software necessary to edit and validate contributions to the Homer Multitext project.



The current VM (available from the `editors-vm` repository) has been used since the summer of 2015. It runs Ubuntu 14.04 with a LXDE GUI, and uses the `morpheus` parsing system to validate the morphology of Greek text.

A new version is currently being developed in the `summer2016` branch of the same repository, and will be the standard VM for the project beginning in the summer of 2016.    It runs [Elementary OS](https://elementary.io/) 0.3, and uses the `Kanōnes` system for parsing and validating the morphology of Greek text.

Documentation linked here is for the current release version (i.e., the summer 2015 standard).  For preliminary documentation of the development version, please [follow this link](vm2016).

## Set up and configuration

- initial [installation](install)
- how to [change or add keyboard layouts](keyboard)
- configure [github settings in your VM](config-github)
- make [Xml Copy Editor](xmlcopyeditor) safe to use
- how to [install the Alpheios plugin for Firefox](alpheios)
- how to [set the character encoding in Firefox](ff-char-enc)
- how to change the time zone.  (This can be important, since version control repositories depend on reliable time-stamps!)
- how to configure your LXTerminal



## Syncing and updating your work ##


- `refresh-hmt.sh`: to refresh/update your HMT tool suite



## Using the VM ##


- how to type Greek

Using applications already installed in the VM:

- for markup, `Xml Copy Editor`
- for markdown, `ReText`.  Note "Preview" toggle to edit/view formatted.
- for text formatting, `pandoc`



## Troubleshooting ##


- How to [fix your files if you accidentally insert the BOM](bom)
