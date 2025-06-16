# AnsiblePull
Personal Ansible Pull Client System Config, minimal installs for systems with minimal storage.

This is the client system configuration for all ubuntu/debian linux systems on the network. this setup relies on freeipa network accounts and not local accounts.



to install:

sudo apt install git ansible -y

sudo ansible-pull -U https://github.com/arunstedler/AnsiblePullClientSystem-Minimal.git
