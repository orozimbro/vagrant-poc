Vagrant.configure("2") do |config|
	
	# box for hyperv (https://app.vagrantup.com/bento/boxes/ubuntu-18.10)
	config.vm.box = "bento/ubuntu-18.10"
	# disabling sync_folder due hyperv-SMB issues
	config.vm.synced_folder ".", "/vagrant", disabled: true
	
	config.vm.define :srv01 do |srv01_config|
		srv01_config.vm.network :private_network, :ip => "192.168.33.10"
		srv01_config.vm.hostname = "srv01"
	end
	
	config.vm.define :srv02 do |srv02_config|
		srv02_config.vm.network :private_network, :ip => "192.168.33.11"
		srv02_config.vm.hostname = "srv02"
	end
	
end
