sudo pacman -Syu ansible
ansible-galaxy install luizgavalda.aur
ansible-galaxy collection install community.general
ansible-galaxy install markosamuli.linuxbrew
ansible-playbook playbook.yml