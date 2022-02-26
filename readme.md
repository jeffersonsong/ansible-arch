`# sudo pacman -Syu ansible git vim`
`# ansible-playbook create_user.yml`

reboot, login as user

`# ansible-galaxy collection install community.general`
`# ansible-galaxy install luizgavalda.aur`

`# ansible-playbook playbook.yml`
# Start from Arch linux

`# ansible-playbook install.yml`

# Start from Arch xfce or Manjaro
`# ansible-playbook base.yml`
`# ansible-playbook dev.yml`

## Install linuxbrew manually

`# ansible-playbook brew.yml`

Error starting domain: Requested operation is not valid: network 'vagrant-libvirt' is not active
https://www.xmodulo.com/network-default-is-not-active.html

sudo virsh net-list --all
sudo virsh net-start vagrant-libvirt
sudo virsh net-autostart vagrant-libvirt


virsh net-autostart default
virsh net-start default

gnome installation
https://gist.github.com/thacoon/96e66f5d475a059cc6d66b61c6366b7a
# Minimal gnome installation
pacman -S gnome-shell gnome-terminal gnome-tweak-tool gnome-control-center xdg-user-dirs gdm

 sudo pacman -S manjaro-gnome-assets manjaro-gdm-theme

gnome-shell
gnome-terminal
gnome-tweak-tool
gnome-control-center
xdg-user-dirs
gdm
gnome-keyring

gdm, gnome-control-center, gnome-tweaks, gnome-terminal and nautilus xdg-user-dirs eog file-roller

# If you want to use a graphical user login
pacman -S gdm3
systemctl start gdm
systemctl enable gdm # If everything works fine, to use gdm automatically
