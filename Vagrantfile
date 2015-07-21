# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

# Ubuntu 12.04 32 bit
config.vm.define "precise32" do |precise32|
  precise32.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  precise32.vm.box = "ubuntu/precise32"
  precise32.vm.network "forwarded_port", guest: 80, host: 81
  precise32.vm.network "private_network", ip: "192.168.80.81"
  precise32.ssh.forward_agent = true
end

# Ubuntu 12.04 64 bit
config.vm.define "precise" do |precise|
  precise.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  precise.vm.box = "ubuntu/precise64"
  precise.vm.network "forwarded_port", guest: 80, host: 82
  precise.vm.network "private_network", ip: "192.168.80.82"
  precise.ssh.forward_agent = true
end

# Ubuntu 14.04 32 bit
config.vm.define "trusty32" do |trusty32|
  trusty32.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  trusty32.vm.box = "ubuntu/trusty32"
  trusty32.vm.network "forwarded_port", guest: 80, host: 83
  trusty32.vm.network "private_network", ip: "192.168.80.83"
  trusty32.ssh.forward_agent = true
end

# Ubuntu 14.04 64 bit
config.vm.define "trusty" do |trusty|
  trusty.vm.provider "virtualbox" do |v|
      v.memory = 512
  end
  trusty.vm.box = "ubuntu/trusty64"
  trusty.vm.network "forwarded_port", guest: 80, host: 84
  trusty.vm.network "private_network", ip: "192.168.80.84"
  trusty.ssh.forward_agent = true
end

# Debian 6 32 bit
config.vm.define "squeeze32" do |squeeze32|
  squeeze32.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  squeeze32.vm.box = "chef/debian-6.0.10-i386"
  squeeze32.vm.network "forwarded_port", guest: 80, host: 85
  squeeze32.vm.network "private_network", ip: "192.168.80.85"
  squeeze32.ssh.forward_agent = true
end

# Debian 6 64 bit
config.vm.define "squeeze" do |squeeze|
  squeeze.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  squeeze.vm.box = "dene/debian-squeeze"
  squeeze.vm.network "forwarded_port", guest: 80, host: 86
  squeeze.vm.network "private_network", ip: "192.168.80.86"
  squeeze.ssh.forward_agent = true
end

# Debian 7 32 bit
config.vm.define "wheezy32" do |wheezy32|
  wheezy32.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  wheezy32.vm.box = "chef/debian-7.6-i386"
  wheezy32.vm.network "forwarded_port", guest: 80, host: 87
  wheezy32.vm.network "private_network", ip: "192.168.80.87"
  wheezy32.ssh.forward_agent = true
end

# Debian 7 64 bit
config.vm.define "wheezy" do |wheezy|
  wheezy.vm.provider "virtualbox" do |v|
      v.memory = 1024
  end
  wheezy.vm.box = "chef/debian-7.6"
  wheezy.vm.network "forwarded_port", guest: 80, host: 88
  wheezy.vm.network "private_network", ip: "192.168.80.88"
  wheezy.ssh.forward_agent = true
end

end
