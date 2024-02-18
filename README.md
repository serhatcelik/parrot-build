Create a virtual environment and activate it (`externally-managed-environment`):

```bash
python3 -m venv venv
source venv/bin/activate
```

Install Ansible and clone this repo:

```bash
python3 -m pip install ansible
git clone https://github.com/serhatcelik/parrot-build
```

Get sudo token and run Ansible playbook to execute the defined tasks:

```bash
cd parrot-build
sudo whoami
ansible-playbook main.yml
cd ..
rm -rf parrot-build
```
