# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.network "public_network", ip: "192.168.1.68",  bridge: 'en1: Wi-Fi (AirPort)'

  config.vm.provider "virtualbox" do |vb|
    # vb.gui = true
  
    vb.customize ["modifyvm", :id, "--memory", "1536"]
  end
end
