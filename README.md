# Ansible Nginx Setup

This project contains Ansible playbooks for:
- Installing and starting Nginx.
- Deploying a static website.

### Usage

1. Edit the `inventory` file with the IP addresses of your servers.
2. Run the playbooks:
   - `ansible-playbook -i inventory playbooks/install_nginx_play.yml`
   - `ansible-playbook -i inventory playbooks/deploy_static_page.yml`

