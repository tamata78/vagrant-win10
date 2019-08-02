# Windows10 using Vagrant

# Setup
Install Vagrant and Virtualbox using homebrew

download windows10 image from URL below
https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/
```
$ brew tap caskroom/cask
$ brew cask install virtualbox
$ brew cask install vagrant
$ vagrant box add [boxファイルへのパス] --name [VM名]
```
```
$ vagrant up
```
