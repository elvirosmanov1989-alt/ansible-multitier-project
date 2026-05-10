# Ansible Multi-Tier Application Deployment

## Project Overview

This project demonstrates the provisioning and deployment of a multi-tier application environment using Ansible automation.

The infrastructure consists of:

* Nginx Load Balancer
* Web Server
* MariaDB Database Server
* Ansible Control Node

---

# Technologies Used

* Ansible
* Ansible Galaxy
* Nginx
* Apache2
* MariaDB
* Ansible Vault
* Linux (RHEL & Ubuntu)

---

# Features

* Automated load balancer deployment
* Automated web server configuration
* Automated database setup
* Secure credential management using Ansible Vault
* Database access restriction
* SSH hardening
* SELinux troubleshooting

---

# Playbooks

```bash id="bq5t7u"
load_balancer.yml
web_servers.yml
database.yml
site.yml
```

---

# Verification

```bash id="z8m3qr"
curl http://192.168.13.128
```

```bash id="f2x9kn"
ansible all -m ping --ask-vault-pass
```

