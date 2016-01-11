# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.network "forwarded_port", guest: 21, host: 21
  config.vm.network "forwarded_port", guest: 21, host: 2121
  config.vm.network "forwarded_port", guest: 10090, host: 10090
  config.vm.network "forwarded_port", guest: 10091, host: 10091
  config.vm.network "forwarded_port", guest: 10092, host: 10092
  config.vm.network "forwarded_port", guest: 10093, host: 10093
  config.vm.network "forwarded_port", guest: 10094, host: 10094
  config.vm.network "forwarded_port", guest: 10095, host: 10095
  config.vm.network "forwarded_port", guest: 10096, host: 10096
  config.vm.network "forwarded_port", guest: 10097, host: 10097
  config.vm.network "forwarded_port", guest: 10098, host: 10098
  config.vm.network "forwarded_port", guest: 10099, host: 10099
  config.vm.network "forwarded_port", guest: 10100, host: 10100

  config.vm.provision :ansible do |ansible|
    ansible.playbook = "playbook.yml"
  end
end
