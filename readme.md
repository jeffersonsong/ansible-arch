sudo pacman -Syu ansible git vim
ansible-galaxy install luizgavalda.aur
ansible-galaxy install monolithprojects.homebrew
ansible-playbook create_user.yml
ansible-playbook playbook.yml