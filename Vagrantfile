# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
  config.vm.box = "archlinux/archlinux"
  config.vm.synced_folder './', '/vagrant'
  config.vm.provider :libvirt do |libvirt|
    libvirt.cpus = 4
    libvirt.memory = 16384    
    libvirt.machine_virtual_size = 30
    libvirt.nested = true
    libvirt.graphics_type = 'spice'
    libvirt.video_type = 'qxl'
    libvirt.sound_type = 'ich9'
  end
end
