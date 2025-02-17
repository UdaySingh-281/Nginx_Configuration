# Ansible Playbook: Install and Configure Nginx

## Overview
This Ansible playbook automates the installation and configuration of Nginx on target machines. It updates the package cache, installs Nginx, and ensures that the service is started.

## Requirements
- Ansible installed on the control node
- Target hosts with Ubuntu/Debian-based OS
- Sudo privileges on the target machines

## Playbook Details

### Tasks Performed:
1. **Update Package Cache**: Ensures the package list is updated.
2. **Install Nginx**: Installs the Nginx web server.
3. **Start Nginx Service**: Ensures Nginx is running.

## Usage

### 1. Clone the repository
```sh
git clone <repository_url>
cd <repository_directory>
