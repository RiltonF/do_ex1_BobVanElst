Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.box_check_update = true
	config.vm.define "lamp" do|lamp|
 	config.vm.network "forwarded_port", guest: 80, host: 8080
 	config.vm.network "public_network"
 	config.vm.hostname = "bob.be"
  end

end
