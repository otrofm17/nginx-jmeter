# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "lb01" do |lb01|
    lb01.vm.box = "ubuntu/trusty64"
    lb01.vm.hostname = "lb01"
    lb01.vm.network :private_network, ip: "10.11.12.50"
  end

  config.vm.define "web01" do |web01|
    web01.vm.box = "ubuntu/trusty64"
    web01.vm.hostname = "web01"
    web01.vm.network :private_network, ip: "10.11.12.51"
  end

  config.vm.define "web02" do |web02|
    web02.vm.box = "ubuntu/trusty64"
    web02.vm.hostname = "web02"
    web02.vm.network :private_network, ip: "10.11.12.52"
  end
end
