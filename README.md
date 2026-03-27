# Ansible Server Configuration Project

## Overview
This project uses Ansible to automate server configuration and management.

## Technologies Used
- Ansible
- Ubuntu Linux
- Nginx
- AWS EC2

## Playbooks
- myplaybook.yml - Configure web server
- handlers-playbook.yml - Demonstrate handlers
- loops-playbook.yml - Demonstrate loops
- variables-playbook.yml - Demonstrate variables
- role-playbook.yml - Demonstrate roles

## What it does
- Installs and configures Nginx web server
- Manages packages on remote servers
- Creates files and directories
- Demonstrates handlers, loops and variables
- Uses roles for organized reusable code

## How to use
1. Install Ansible
2. Update inventory.ini with your server IP
3. Run ansible-playbook -i inventory.ini playbook.yml

## Author
Balogun Ibrahim - Cloud DevOps Engineer

