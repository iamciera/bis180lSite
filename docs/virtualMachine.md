---
layout: default
---

# Instructions on installing and using the BIS180L virtual linux machine

## About
Most bioinformatics software runs on linux or unix (including MAC) computers.  For this class we will work in a linux environment.  Since the computer labs have Windows machines we will run linux in a virtual environment.

Specifically we will run a program called [VirtualBox](https://www.virtualbox.org/) on the Windows machine ([more info](http://en.wikipedia.org/wiki/VirtualBox)).  Virtualbox creates a virtual machine, hosted on the Windows PC, which will run linux.  The virtual linux machine has a virtual disk which will live on your flash drive.  This way files that you save can be used from class to class.  In addition you can install virtualbox on your personal computer, insert the flashdrive, and use the same virtual linux machine that you are using here.

If you are curious about what version of linux we are using, and what programs I installed, please see the document "Creating the machine image" on SmartSite resources.

## Format the flash drive as "ExFat"
Your flash drive is probably formatted in "Fat32" format.  This file format has a limitation of 4GB for maximum file size.  The file containing the linux virtual drive is ~ 8GB so we need to change the format of the flash drive.  *This only needs to be done once*

** Warning this will erase all files on your flash drive **

* Insert your flash drive into a USB port
* Click on the "Start" menu, lower left, and then click on computer.
* Right click on the flash drive (probably labelled "E:..." or  "F:...")
* Choose "Format"
* Choose "ExFat"
* Click "Start" and then "OK"



(Will be demoed in class)


## Get the BIS180L image

Follow the instructions given in class to find the BIS180L_lubuntu64 folder
Drag the folder onto your newly formatted flash drive.

## Unpack and start the virtual machine.

Look inside the BIS180L_lubuntu64 folder on your flash drive.  There will be several files.

* "BIS180L_lubuntu64.vdi"--this is the virtual disk drive
* "BIS180L_lubuntu64.vbox"--this contains information about the virtual machine.

Double click the "BIS180L_lubuntu64.vbox" file.  This should start the virtual machine.  You may need to press "start" in the virtualbox window.  It will take a about 1 minute to boot.  When the boot is complete you should see a window that looks like this (see next page):

![BIS180L linux desktop](file:///Users/jmaloof/Dropbox/Notational images/BIS180L_screenshot.png)


## Username and Password

The machine is set to logon the user automatically.  But if you need the username and password they are:

username: bios180student

password: bioinformatics

## Using the machine.

You can resize the "screen" by dragging from the lower-right corner.

You should be able to cut and paste between your host machine and the virtual machine.  Mac users note that inside the virtual machine you will need to use ctrl-C, not CMD-c, etc.  Also the cut and paste commands for the terminal are shift-ctrl-C and shift-ctrl-V.

The icons at the bottom left give you access to various programs.  

From left to right:

* Start menu.  This gives you access to system preferences and a variety of programs.
* File manager.  Equivalent to the Mac "Finder" or Windows "Explorer"
* Terminal.  Access the linux comand line.
* gedit.  A text editor for programming.
* Firefox.
* Abiword, a word processor.
* Gnumeric, a spreadsheet application
* A PDF viewer
* Rstudio
* IGV
* Jalview
* Cytoscape
* This button will collapse windows
* This button allows you to switch desktops

## Install VirtualBox at home

If you want to do this at home you need to install VirtualBox.  It is free.

Download and install [VirtualBox](https://www.virtualbox.org/)

Direct link to [download page.](https://www.virtualbox.org/wiki/Downloads)  You do not need the extension pack.
