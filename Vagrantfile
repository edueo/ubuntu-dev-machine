# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  
  config.vm.hostname = "ubuntu-dev-machine2"
 
  config.vm.network "public_network"

  config.vm.provision "shell", path: "./provision-dev-vm.sh"
end
