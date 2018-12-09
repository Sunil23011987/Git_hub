Vagrant.configure("2") do |config|
   config.vm.define "Ubuntu16" do |ubuntu|    
        ubuntu.vm.box = "ubuntu/trusty64"
        ubuntu.vm.host_name = 'Ubutnu-16'
        # You may wish to use a more obscure private ip, like 10.2.2.4
        ubuntu.vm.network "private_network", ip: "10.0.0.200"
  end
  config.vm.define "Centos7" do |centos|    
        centos.vm.box = "centos/7"
        centos.vm.host_name = 'Centos7'
        # You may wish to use a more obscure private ip, like 10.2.2.5
        centos.vm.network "private_network", ip: "10.0.0.201"
  end
end