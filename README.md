# vagrant-vms
Vagrantfiles for various development environments

# Requirements
In order to run virtual machines from this project, VirtualBox and Vagrant are needed.

# Vagrant plugins
Plugin vagrant-triggers is required. Pure Vagrant does not have a tear down hook to run a script before shutting down, reloading or destroying a VM.

In order to install the plugin:
```
vagrant plugin install vagrant-triggers
```

Plugin vagrant-hostupdater is optional. It updates hosts file in the host operating system with the mapping to the guest operating system. Therefore, using the hostname is possible, not only referring by IP address or setting up SSH tunnels.

In order to install the plugin:
```
vagrant plugin install vagrant-hostsupdater
```

Plugin vagrant-vbox-snapshot is optional. It enables using VirtualBox snapshots via Vagrant.

In order to install the plugin:
```
vagrant plugin install vagrant-vbox-snapshot
```
