## Ubuntu

```
sudo apt install -y software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt update
sudo apt install -y ansible git
```

## All

```
ansible-galaxy install -r requirements.yaml
ansible-galaxy install collection -r requirements.yaml
ansible-playbook main.yaml --ask-become-pass
```

For screen resolution see: https://www.tecmint.com/set-display-screen-resolution-in-ubuntu/
