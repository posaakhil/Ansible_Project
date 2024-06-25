# Ansible Ubuntu setup
Ansible roles to setup Ubuntu desktop and Ubuntu server (14.04 and 16.04). This playbook is focused on quickly deploying a "ready to use" dev machine.


## Requirements
- Git
- Ansible 2+ (automatically installed from [Ansible offical PPA]with the provided install.sh script)


## Installation
First, you need to install Git and Ansible :
```
sudo apt-get install git
git clone https://github.com/posaakhil/ansible-project.git
cd ansible-project
./install.sh
```

Then you need to customize the playbook `ansible-desktop.yml` (or create a new one) to suit your needs. Every roles are disabled by default.

Run `ansible-playbook ansible-desktop.yml --ask-become-pass` and enter your sudo password to run the playbook

