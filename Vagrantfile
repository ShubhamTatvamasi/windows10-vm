Vagrant.configure("2") do |config|

  config.vm.box = "gusztavvargadr/windows-10"
  config.vm.hostname = "windows-10"
  config.vm.box_version = "2101.0.2106"
  config.vbguest.auto_update = false

  config.vm.synced_folder "data/", "/vagrant"

  config.vm.provider "virtualbox" do |v|

    v.name = "windows-10"
    v.linked_clone = true
    # v.gui = true
    v.memory = 4096
    v.cpus = 2

    v.customize ["modifyvm", :id, "--vram", "128"]
    v.customize ["modifyvm", :id, "--accelerate3d", "on"]

  end

end
