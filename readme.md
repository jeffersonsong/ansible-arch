sudo pacman -Syu ansible git vim
ansible-galaxy install luizgavalda.aur

# ansible-playbook create_user.yml
ansible-playbook install.yml

ansible-galaxy install monolithprojects.homebrew
ansible-playbook playbook.yml