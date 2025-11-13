# ansible-config_pdns_content

[![Galaxy Role](https://img.shields.io/badge/galaxy-config_pdns_content-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/config_pdns_content)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-config_pdns_content.svg)](https://github.com/lotusnoir/ansible-config_pdns_content/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-config_pdns_content?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/config_pdns_content)
[![downloads](https://img.shields.io/ansible/role/d/lotusnoir/config_pdns_content)](https://galaxy.ansible.com/lotusnoir/config_pdns_content)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Add records inside powerdns thru api, can create all zone typoes and manage auto ptr, for large amounts of records we shouldnt use this role as it takes time

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: config_pdns_content
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-config_pdns_content

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
