Install Ansible and clone this repo to your home directory:

```bash
python3 -m pip install ansible && cd ~ && git clone https://github.com/serhatcelik/parrot-build
```

Get sudo token and run Ansible playbook to execute the defined tasks:

```bash
sudo whoami && ansible-playbook ~/parrot-build/main.yml
```
