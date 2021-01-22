# README

## Installation

1. Clone repo.
2. Install required ansible roles.
3. Run playbook.

```sh
git clone git@github.com:iamskok/rpi-home.git
ansible-galaxy role install -r roles.yml
ansible-galaxy collection install -r collections.yml
ansible-playbook -i inventory provision.yml
```
