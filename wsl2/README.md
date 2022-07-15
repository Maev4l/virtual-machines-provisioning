## WSL2 - Ubuntu

```
python3 -m pip install --user ansible
```

## All

```
ansible-galaxy install -r requirements.yaml
ansible-galaxy collection install -r requirements.yaml
ansible-playbook main.yaml --ask-become-pass --extra-vars "git_username=<username> git_email=<email>"
```
