## Instructions:

- Install Ubunut 16.04 Dektop
- `sudo apt update && sudo apt upgrade -y`
- Install Ansible - http://docs.ansible.com/ansible/latest/intro_installation.html#latest-releases-via-apt-ubuntu
- `cd && mkdir Code && cd Code`
- `sudo apt install git`
- `git clone git@github.com:nicklaw5/ansible-ubuntu-16-04-desktop.git && cd ansible-ubuntu-16-04-desktop`
- `ansible-galaxy install -r requirements.yml --extra-vars "ansible_sudo_pass=<system_user_password>"`
