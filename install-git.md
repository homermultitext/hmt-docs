---
layout: page
title: Installing Git
---

Git is the version control system we use for the HMT project.

## If you're running Mac OS X 10.7.5


- Go to [this page](https://code.google.com/p/git-osx-installer/downloads/detail?name=git-1.8.4.2-intel-universal-snow-leopard.dmg&can=2&q=) and download Git 1.8.4.2
- Run that installer. When it is done, close your Terminal window and open another one.
- Confirm that it works by typing `git --version`.


## Other users ##

You can install git by going to <https://git-scm.com/>. 


## Troublehshooting: if you install the wrong version on  Mac OS X 10.7.5

If you have problems like the description on [this page](http://stackoverflow.com/questions/23448318/git-segmentation-fault-11), you need to uninstall this version of git

- Open the disk-image from which you originally installed Git. It will have a name like "Git Install…".
- In the terminal, type `cd /Volumes/Git<TAB>` to navigate to that disk-image.
- Type `./uninstall.sh`, type "yes" when it asked, then your password.
- Confirm that you have uninstalled Git by typing `which git` in the Terminal. There should be no answer.

Then install following the instructions above.


