sudo pacman -Syu ansible
ansible-galaxy collection install community.general
ansible-galaxy install markosamuli.linuxbrew
ansible-playbook playbook.yml