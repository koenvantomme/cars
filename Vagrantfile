# config for jumpserver
# config for nodes

Vagrant.configure("2") do |config|
#  config.ssh.insert_key = false
  config.vm.define "jumpserver01" do |jumpserver01|
    jumpserver01.vm.box = "centos/7"
    jumpserver01.vm.hostname= 'jumpserver1'
    jumpserver01.vm.box_url= 'jumpserver1'
    jumpserver01.vm.network "private_network", ip: "10.0.33.200"
    jumpserver01.vm.network 'forwarded_port', guest: 80, host: 8081
    #jumpserver01.vm.provision :ansible do |ansible|
    #  ansible.playbook = "jumpserverprovision.yml"
    #end
  end

  config.vm.define "kafka01" do |kafka01|
    kafka01.vm.box = "centos/7"
    kafka01.vm.hostname= 'kafka01'
    kafka01.vm.box_url= 'kafka01'
    kafka01.vm.network "private_network", ip: "10.0.33.201"
    kafka01.vm.network 'forwarded_port', guest: 80, host: 8082
    #kafka01.vm.provision :ansible do |ansible|
    #  ansible.playbook = "kafkanodeprovision.yml"
    #end
  end

  config.vm.define "kafka02" do |kafka02|
    kafka02.vm.box = "centos/7"
    kafka02.vm.hostname= 'kafka02'
    kafka02.vm.box_url= 'kafka02'
    kafka02.vm.network "private_network", ip: "10.0.33.202"
    kafka02.vm.network 'forwarded_port', guest: 80, host: 8083
    #kafka02.vm.provision :ansible do |ansible|
    #  ansible.playbook = "kafkanodeprovision.yml"
    #end
  end

  config.vm.define "kafka03" do |kafka03|
    kafka03.vm.box = "centos/7"
    kafka03.vm.hostname= 'kafka03'
    kafka03.vm.box_url= 'kafka03'
    kafka03.vm.network "private_network", ip: "10.0.33.203"
    kafka03.vm.network 'forwarded_port', guest: 80, host: 8084
    #kafka03.vm.provision :ansible do |ansible|
    #  ansible.playbook = "kafkanodeprovision.yml"
    #end
  end

  config.vm.define "kafka04" do |kafka04|
    kafka04.vm.box = "centos/7"
    kafka04.vm.hostname= 'kafka04'
    kafka04.vm.box_url= 'kafka04'
    kafka04.vm.network "private_network", ip: "10.0.33.204"
    kafka04.vm.network 'forwarded_port', guest: 80, host: 8085
    #kafka04.vm.provision :ansible do |ansible|
    #  ansible.playbook = "kafkanodeprovision.yml"
    #end
  end
end
