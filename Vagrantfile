# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "debian/jessie64"

  config.vm.network "private_network", ip: "192.168.33.42"

  config.vm.hostname = "minecraft"

  config.vm.provider "virtualbox" do |v|
    v.name = "ansible-minecraft"
  end
  config.vm.provision "ansible" do |ansible|
    ansible.verbose = "v"
    ansible.playbook = "tests/test.yml"
  end
end
