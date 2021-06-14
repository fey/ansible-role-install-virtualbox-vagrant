# Ansible playbook to install Virtualbox and Vagrant

[![Build Status](https://travis-ci.org/aeimer/ansible-role-install-virtualbox-vagrant.svg?branch=master)](https://travis-ci.org/aeimer/ansible-role-install-virtualbox-vagrant)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-install--virtualbox--vagrant-660198.svg)](https://galaxy.ansible.com/aeimer/install-virtualbox-vagrant/)

Ansible Galaxy page: [https://galaxy.ansible.com/fey/install-virtualbox-vagrant/](https://galaxy.ansible.com/fey/install-virtualbox-vagrant/).

Fork of [https://github.com/aeimer/ansible-role-install-virtualbox-vagrant](https://github.com/aeimer/ansible-role-install-virtualbox-vagrant).

## Variables

| Name                       | Default Value    | Description                                                 |
| -------------------------- | ---------------- | ----------------------------------------------------------- |
| virtualbox_version         | `6.1.22`         | Sets the version number which should be installed           |
| virtualbox_apt_key_url     | ...              | The url of the VB apt key                                   |
| virtualbox_apt_key_url_old | ...              | The url of the VB apt key for older OS's                    |
| virtualbox_apt_repo_url    | ...              | The url of the VB repository                                |
| virtualbox_users           | `[]`             | An Array of usernames which should be added to the VB-Group |
| vagrant_version            | `2.2.16`         | Sets the version number which should be installed           |
| vagrant_deb_url            | ...              | The url to download the debian package                      |
| vagrant_deb_sha_url        | ...              | The url to download the sha256 of the debain package        |

## Example Playbook

```YAML
- hosts: localhost
  roles:
    - fey.install_virtualbox_vagrant
```
