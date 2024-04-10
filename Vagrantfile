# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box= "ubuntu/trusty64"

  # Define a base VM configuration
  base_config = {
    vm: {
      box: "ubuntu/trusty64",
    }
  }

  # Create the first VM
  config.vm.define "first", base_config.merge({}) do |vm|
  end

  # Create the second VM
  config.vm.define "second", base_config.merge({}) do |vm|
  end

  # Create the third VM
  config.vm.define "third", base_config.merge({}) do |vm|
  end

end

