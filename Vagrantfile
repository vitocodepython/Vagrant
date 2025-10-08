Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp-education/ubuntu-24-04"
  config.vm.box_version = "0.1.0"

  config.vm.define "vitoS" do |node|
    node.vm.hostname = "vitoS"
    node.vm.network "private_network", ip: "192.168.56.110"
  end

  config.vm.define "KizaruSW" do |node|
    node.vm.hostname = "KizaruSW"
    node.vm.network "private_network", ip: "192.168.56.111"
  end
end
