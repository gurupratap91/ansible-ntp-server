# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu-trusty64"

  config.vm.define "host" do |test|
  test.vm.network "private_network", ip: "192.168.20.4"
  end

  config.vm.define "client" do |test|
  test.vm.network "private_network", ip: "192.168.20.5"
  end
end
