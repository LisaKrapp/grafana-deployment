# Grafana Ansible Deployment

Welcome to this Ansible project designed to automate the installation of Grafana, a widely used open-source platform for monitoring and observability.

## Project Overview

The main playbook in this project is:

grafana-deployment.yml

It uses the role:

install-grafana

This role handles the setup and configuration of Grafana on your target system.

## Usage

To deploy Grafana, run:

```bash
ansible-playbook grafana-deployment.yml
```

Ensure your inventory and any required variables are properly configured before executing the playbook.

## Notes
This project is intended as a simple and reusable automation for Grafana installation. Feel free to adapt it to your environment or contribute improvements.