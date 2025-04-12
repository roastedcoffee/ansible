# Ansible Setup and Playbook Execution

This guide explains how to set up a Python environment and run your Ansible playbook on a Linux system. The steps below will help you install the necessary dependencies, create a virtual environment, install Ansible, and run the playbook.

---

## Prerequisites

- A Linux system with `sudo` privileges.
- Internet access to download packages.

---

## Installation Steps

1. **Update Package List & Install Python 3.8 and Virtual Environment Tools**

   Open a terminal and run:

   ```bash
   sudo apt update && sudo apt install python3.8 python3.8-venv python3.8-dev -y && python3.8 -m venv ansible-env && source ansible-env/bin/activate && pip install --upgrade pip && pip install ansible sudo apt-get install build-essential libffi-dev libssl-dev python-dev python3-dev python3 -m pip install --upgrade pip setuptools wheel

 2. #Run the Ansible Playbook
   ```bash
ansible-playbook getslxver.yaml -i inventory.ini
