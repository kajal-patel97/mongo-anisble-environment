
Vagrant.configure("2") do |config|
#This is the box that it is going to run off- the interface it uses.
  config.vm.box = "ubuntu/xenial64"
# The network that it is going to run off
  config.vm.network "private_network", ip: "192.168.10.150"
# The alias the ip address is going to need eg. website. Putting it in square brackets allows it to have more than one aliases
  config.hostupdater.aliases = ["database.local"]
# synced folders enable vagrant o sync a folder on the host machine to the guest machine
  # the first parameters is the path on the host machine and the second parameter is on the guest machine (vm )
  config.vm.synced_folder "environment/db" , "vagrant/envrionment/db "

end
