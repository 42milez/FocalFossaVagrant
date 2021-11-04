# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # https://app.vagrantup.com/generic/boxes/ubuntu2004
  config.vm.box = "generic/ubuntu2004"
  config.vm.box_version = "3.5.0"
  config.vm.provider "vmware_desktop" do |v|
    v.vmx["memsize"] = "1024"
    v.vmx["numvcpus"] = "2"
  end
end
