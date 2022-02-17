sudo pacman -Syu ansible git vim
#ansible-galaxy install luizgavalda.aur
#ansible-galaxy collection install community.general
#ansible-galaxy install monolithprojects.homebrew
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml