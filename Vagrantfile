# -*- mode: ruby -*-

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/wily64"
  config.vm.provider "virtualbox" do |vb|
    vb.gui = true
    vb.memory = "1024"
  end

  config.vm.provision :shell, path: "provisioning/bootstrap.sh", privileged: false  
end
