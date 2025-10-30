# Fake Ansible Playbooks Repository

This repository contains a collection of fake Ansible playbooks designed for testing and demonstration purposes. Each playbook simulates common IT tasks without making any actual changes to systems.

## Playbooks Included

- playbooks/basic_server.yml — Basic server setup (users, packages, services)  
- playbooks/database.yml — Database installation and configuration (mock)  
- playbooks/ec2.yml — EC2 instance provisioning simulation  
- playbooks/flask_app.yml — Deploy a sample Flask application  
- playbooks/network_verification.yml — Network troubleshooting playbook (simulated)  
- playbooks/simulate_user.yml — Create and manage fake users  
- playbooks/ssh_hardening.yml — Simulate SSH hardening tasks  
- playbooks/web_server.yml — Configure a simple web server (nginx/httpd) 

## Usage

To run any of the playbooks, use the following command:

```bash
ansible-playbook playbooks/<playbook_name>.yml
```