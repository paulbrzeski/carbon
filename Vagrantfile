Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"
  config.vm.define "xenial" do |server|
    server.vm.network "private_network", ip: "192.168.10.10"
  end
end
