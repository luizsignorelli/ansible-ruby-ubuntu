Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = 'test.yml'
    ansible.limit = 'all'
    ansible.verbose = 'v'
  end
end
