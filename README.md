# Debian Config
Configuration file for Debian-based Linux operating systems, primarily designed for penetration tests and CTF games.
## Prerequisite:
Install Ansible
```
$ python -m pip install --user ansible
```
### Run config
Terminal command to provide root password for the process:
```
ansible-pull -U "repository-name" --ask-become-pass
```
