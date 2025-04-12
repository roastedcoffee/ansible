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
   sudo apt update && sudo apt install python3.8 python3.8-venv python3.8-dev -y
