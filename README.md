# ansible-vagrant-host

Installs Vagrant on host machine, pre-packages virtualbox. Installation of
Vagrant and VirtualBox are executed using the debian packages provided by both
projects.

[VirtualBox](https://www.virtualbox.org)<br>
[Vagrant](https://www.vagrantup.com)

## Requirements

- Ubuntu 18.04
- Ansible 2.7+
- Requires root privilages on host machine

## Packages Installed by this playbook

- Git:latest
- Vim:latest
- VirtualBox:5.2_5.2.22-126460
- Vagrant:2.2.2_x86_64

## Getting Started

To execute run:
```command
ansible-playbook playbook.yml
```

