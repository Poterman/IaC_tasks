# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.

$script=<<-SCRIPT
echo "this is where provisioning is happening"

SCRIPT



Vagrant.configure("2") do |config|
  config.vm.define "server" do |s|
     s.vm.box="centos/7"
     s.vm.hostname="server"
     s.vm.network "private_network", ip: "10.0.220.100"
     s.vm.provision "shell", inline: $script
  end

  config.vm.define "client" do |c|
     c.vm.box="centos/7"
     c.vm.hostname="client"
     c.vm.network "private_network", ip: "10.0.220.101"
     c.vm.provision "shell", inline: $script
  end


end
