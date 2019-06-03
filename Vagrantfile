# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vm.box_check_update = false

  config.vm.define "otusswarm1" do |otusswarm1|
    otusswarm1.vm.hostname = "otus-swarm-1"
    otusswarm1.vm.network "private_network", ip: "192.168.50.10"
    config.vm.provider "virtualbox" do |otusswarm1|
      otusswarm1.memory = "1024"
      otusswarm1.cpus = "2"
  end
  end

  config.vm.define "otusswarm2" do |otusswarm2|
    otusswarm2.vm.hostname = "otus-swarm-2"
    otusswarm2.vm.network "private_network", ip: "192.168.50.11"
    config.vm.provider "virtualbox" do |otusswarm2|
      otusswarm2.memory = "1024"
      otusswarm2.cpus = "2"
  end
  end

  config.vm.define "otusswarm3" do |otusswarm3|
    otusswarm3.vm.hostname = "otus-swarm-3.local"
    otusswarm3.vm.network "private_network", ip: "192.168.50.12"
    config.vm.provider "virtualbox" do |otusswarm3|
      otusswarm3.memory = "1024"
      otusswarm3.cpus = "2"
  end
  end
end