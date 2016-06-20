---
title:  "HMT VM: development version"
layout: page
---

The HMT project VM for editors is a virtual machine including all the software necessary to edit and validate contributions to the Homer Multitext project.

This page describes the VM currently in use in the summer of 2016.


It runs [Elementary OS](https://elementary.io/) 0.3, and uses the `kanōnes` system for parsing and validating the morphology of Greek text.



## Set up and configuration

- initial [installation](install)
- how to [change or add keyboard layouts](keyboard)
- configure [github settings in your VM](config-github)
- make [Xml Copy Editor](xmlcopyeditor) safe to use
- how to [install the Alpheios plugin for Firefox](alpheios)
- how to [set the character encoding in Firefox](ff-char-enc)




## Syncing and updating your work ##


- `refresh-hmt.sh`: to refresh/update your HMT tool suite



## Using the VM ##


- [how to type polytonic Greek](greek)

Using applications already installed in the VM:

- for markup, `Xml Copy Editor`
- for markdown, `Atom` (<https://atom.io/>).  To display a formatted view of your markdown document, you can use the Markdown Preview package (`Packages` menu, `Markdown Preview`, or from the keyboard `ctl-shift-M`)
- for text formatting, `pandoc` ([pandoc.org](http://pandoc.org/))



## Troubleshooting ##


- How to [fix your files if you accidentally insert the BOM](bom)
