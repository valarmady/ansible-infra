# Valarmady - Ansible Infrastructure

This repository contains Ansible roles and playbooks for provisioning and hardening systems, installing Docker, and setting up GitLab.

---

## Repository Structure

```text
valarmady/
├── init/                  # Initialize the system configuration
├── ssh_hardening/         # Role to secure SSH and harden the system
├── docker_install/        # Role to install and configure Docker
├── install_gitlab/        # Role to install and configure GitLab
├── inventory/             # Environment inventories
├── deployment.yml         # Main deployment playbook
