# Ansible Role - Ansible Dev Environment

Ansible role to setup an Ansible dev environment.

<!-- ## Usage -->

## Development

> First, you need **python3.10** and **docker** installed on your system.

To setup the development environment, run:

```bash
# Ubuntu/Debian
sudo apt-get update && sudo apt-get install -y python3-pip python3-venv
# RedHat
sudo dnf install -y python3-pip python3-venv

# Virtual env and python packages
python3 -m venv ansible
source ansible/bin/activate
pip install -r dev-requirements.txt
```

After this, to test the role:

```bash
molecule test
```
