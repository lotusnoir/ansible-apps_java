# ansible-apps_java

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_java-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_java)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_java.svg)](https://github.com/lotusnoir/ansible-apps_java/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_java?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_java)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_java)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_java)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Deploy java using ansible.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_java
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_java


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

