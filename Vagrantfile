Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"
  
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "playbook.yaml"
  end
end
