
Vagrant::Config.run do |config|
  config.vm.box = "lucid32"
  config.vm.box_url = "http://files.vagrantup.com/lucid32.box"
  config.vm.provision :shell, :path => 'install'
  config.vm.forward_port 8080, 8081
  config.vm.forward_port 23, 2201
  config.vm.forward_port 2003, 2003
end
