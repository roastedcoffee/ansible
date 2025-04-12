# Prep the environment
sudo apt update && sudo apt install python3.8 python3.8-venv python3.8-dev -y && python3.8 -m venv ansible-env && source ansible-env/bin/activate && pip install --upgrade pip && pip install ansible
sudo apt-get install build-essential libffi-dev libssl-dev python-dev python3-dev
python3 -m pip install --upgrade pip setuptools wheel

#Run the Ansible Playbook
ansible-playbook getslxver.yaml -i inventory.ini
