[![Build Status](https://travis-ci.org/aeimer/ansible-role-install-virtualbox-vagrant.svg?branch=master)](https://travis-ci.org/aeimer/ansible-role-install-virtualbox-vagrant)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-install--virtualbox--vagrant-660198.svg)](https://galaxy.ansible.com/aeimer/install-virtualbox-vagrant/)


# Ansible playbook to install Virtualbox and Vagrant

**THIS IS CURRENTLY IN DEVELOP**

Ansible Galaxy page: https://galaxy.ansible.com/aeimer/install-virtualbox-vagrant/

## Variables

| Name | Default Value | Description |
| ---- | ------------- | ----------- |
| virtualbox.version | ??? | Sets the version number which should be installed |
| vagrant.version | ??? | Sets the version number which should be installed |

## Example Playbook
```YAML
- hosts: localhost
  roles:
    - aeimer.install-virtualbox-vagrant
```

