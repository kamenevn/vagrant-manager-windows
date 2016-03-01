# Vagrant Manager for Windows

**--- This project is back under active development ---**

Vagrant Manager is a Windows status bar menu app that lets you manage all of your vagrant machines from one central location.

![Vagrant Manager in actiont](http://hassanally.net/vagrant-manager/windows/vagrant-manager-windows.gif "Vagrant Manager")

## Installation Notes
* Vagrant Manager can automatically detect most machines, undetected machines will require manual configuration via bookmarks.
* Make sure that you have Vagrant installed, and the `vagrant` command is in your path so that Vagrant Manager can execute it
* Currently, vagrant machines must already be initialized in order for Vagrant Manager to detect them. Make sure you have run vagrant init on any machine you want to appear in Vagrant Manager. Once Vagrant Manager has detected a machine, you can bookmark it so that it will not disappear when you destroy the machine. You can also manually add bookmarks and specify the path to your Vagrantfile
