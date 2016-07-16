Vagrant.configure("2") do |config|
  config.vm.box = "TWNIC_Lab"
  config.vm.provider "virtualbox" do |vb|
     vb.memory = "1024"
  end
  config.vm.network "forwarded_port", guest: 8787, host: 8787
end
