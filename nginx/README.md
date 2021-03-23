# Flywheel script to create initial nginx config files

If you want to set up several web sites on a single server,
using [nginx server blocks](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-20-04#step-5-%E2%80%93-setting-up-server-blocks-%28recommended%29),
you need to create nearly identical nginx configuration files for each site hosted on that server.

## Prerequisites

* Java 11 or better.
* [panopset.jar](https://panopset.com/download.html) in your home directory.

## Linux, Mac or Windows Powershell

    java -cp ~/panopset.jar com.panopset.flywheel.Flywheel go.txt target

## Windows Terminal

    java -cp %userprofile%\panopset.jar com.panopset.flywheel.Flywheel go.txt target
    
# In General

Any time you are faced with a tedious task that requires typing the same thing over and over
again, consider trying Panopset Flywheel.  

There are many other template engines out there, 
but how many are [open source](https://github.com/panopset/flywheel), extensible and freeform, with just seven easy to learn commands?
