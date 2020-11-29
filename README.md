# 389ds-proxmox
This project is for installing 389 Directory Server with multi master mode

# Required Environments
Before run ansible playbook it should be set essential parameters

```bash
# export ANSIBLE_USER='xxxxx'
# export ANSIBLE_PASS='changeme^^'

# export PROXMOX_USER='xxxxx@pam'
# export PROXMOX_PASS='changeme^^'
# export PROXMOX_HOST='X.X.X.X'
# export PROXMOX_NODE='pve'

# export DNS_HOST='X.X.X.X'
# export DNS_KEY='dns.key'
# export DNS_SECRET='xxxxx xxxxx=='

```

# Usage
Run ansible playbook for creating 389ds vm

```bash
# ansible -i hosts 389ds-proxmox.yaml

```
