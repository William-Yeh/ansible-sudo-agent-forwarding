Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  #config.vm.box = "ubuntu/precise64"
  #config.vm.box = "bento/centos-6.7"
  #config.vm.box = "bento/centos-7.2"
  #config.vm.box = "debian/jessie64"
  #config.vm.box = "debian/wheezy64"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "test.yml"

    config.ssh.forward_agent = true
  end
end
