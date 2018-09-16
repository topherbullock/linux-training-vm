Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.provision "shell", path: "scripts/configure"
  config.vm.synced_folder "./workspace", "/home/vagrant/", create: true
end
