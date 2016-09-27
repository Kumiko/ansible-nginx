# Ansible nginx role

This Ansible role will install the nginx HTTP server from the main
Ubuntu repository. The role is tested and designed for use on Ubuntu 16.04.

## Installation

```
cd roles

git clone https://github.com/Kumiko/ansible-nginx.git nginx
```

## Usage

Include the role in your playbook:

```
- hosts: your_nginx_hosts
  roles:
    - name: nginx
```
