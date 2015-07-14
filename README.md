# vagrant-vms
Vagrantfiles for various development environments

# Requirements
In order to run virtual machines from this project, VirtualBox and Vagrant are needed.

# Recommended Vagrant plugins

Plugin vagrant-hostupdater updates hosts file in the host operating system with the mapping to the guest operating system. Therefore, using the hostname is possible, not only referring by IP address or setting up SSH tunnels.

In order to install the plugin:
```
vagrant plugin install vagrant-hostsupdater
```

Plugin vagrant-vbox-snapshot enables using VirtualBox snapshots via Vagrant.

In order to install the plugin:
```
vagrant plugin install vagrant-vbox-snapshot
```
