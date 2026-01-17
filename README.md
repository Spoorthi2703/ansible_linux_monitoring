## Automated Linux Server Health Monitoring using Ansible

## Description
This project automates monitoring of Linux server health using Ansible.

## Features
- Collects uptime, memory usage, and disk utilization
- Uses Ansible playbooks for automation
- Works across multiple Linux servers

## Tech Stack
- Ansible
- Linux (Amazon Linux)
- AWS EC2

## Advanced Features
- Uses conditional logic to detect high disk usage
- Implements Ansible `when`, `register`, and `set_fact`
- Provides automated health visibility across Linux servers


## How to Run
1. Configure inventory with target servers
2. Run: ansible-playbook -i inventory.ini monitoring.yaml
