# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  
  config.vm.box = "base-ubuntu-trusty-server"
  config.vm.box_url = "https://cloud-images.ubuntu.com/vagrant/trusty/current/trusty-server-cloudimg-amd64-vagrant-disk1.box"

  config.vm.provider :virtualbox do |vb|
    vb.gui = false
    vb.customize ["modifyvm", :id, "--memory", "1024"]
  end

  config.vm.provision :ansible do |ansible|
    ansible.playbook = "provisioning/playbook.yml"
    ansible.host_key_checking = false
  end

  config.vm.define :elastic_0_90_13 do |cfg|
      cfg.vm.network :private_network, ip: "192.168.33.109"
      cfg.vm.provider :virtualbox do |v|
          v.name = "elastic_0_90_13"
      end
  end

  config.vm.define :elastic_1_3_2 do |cfg|
      cfg.vm.network :private_network, ip: "192.168.33.132"
      cfg.vm.provider :virtualbox do |v|
          v.name = "elastic_1_3_2"
      end
  end

  config.vm.define :elastic_1_4_1 do |cfg|
      cfg.vm.network :private_network, ip: "192.168.33.141"
      cfg.vm.provider :virtualbox do |v|
          v.name = "elastic_1_4_1"
      end
  end
  
end
