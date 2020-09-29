Ansible playbook/roles for setup of workstation

# Install Ansible and other dependencies

All OSes requires an ssh key setup and working with github

## macos

Generate ssh key and upload to github

```
sh setupmac.sh
```

## Ubuntu (20.04 or later)

Generate ssh key and upload to github

```
sudo apt install ansible

ansible-playbook install.yml
```

## Arch Linux

Generate ssh key and upload to github

```
pacman -S ansible

ansible-playbook install.yml
```

# Manual steps

## Carbon Copy Cloner

Install and setup appropriate tasks.

## Iterm2

Import `iterm.json`
