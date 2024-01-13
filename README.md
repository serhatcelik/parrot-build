Create a virtual environment and activate it (externally-managed-environment):

```bash
python3 -m venv ~/venv && . ~/venv/bin/activate
```

Install Ansible and clone this repo to your home directory:

```bash
python3 -m pip install ansible && git clone https://github.com/serhatcelik/parrot-build ~/parrot-build
```

Get sudo token and run Ansible playbook to execute the defined tasks:

```bash
sudo whoami && ansible-playbook ~/parrot-build/main.yml
```
