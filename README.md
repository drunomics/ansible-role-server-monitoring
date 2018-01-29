# drunomics.tool-installer
[![Build Status](https://travis-ci.org/drunomics/ansible-role-tool-installer.svg?branch=master)](https://travis-ci.org/drunomics/ansible-role-tool-installer)

Ansible role that installs various tools by downloading them.

Distribution: Ubuntu (tested on 16.04)

## Requirements
None.

## Dependencies
None.

## Supported variables

Example which will install the tool phapp:
  
    tool_installer:
      phapp:
        url: https://github.com/drunomics/phapp-cli/releases/download/0.6.0-beta1/phapp.phar
        version: 0.6.0-beta1

Please check the documented variables defaults/main.yml.


(c) 2018 drunomics GmbH. /  MIT License
