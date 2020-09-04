---
title: 'SSH keys'
taxonomy:
    category:
        - docs
---

## SSH Keys
### Generate SSH key
- Basic SSH key: `ssh-keygen -t rsa -b 4096`
- SSH key for Github `ssh-keygen -t rsa -b 4096 -C "your@email.com"` 

### Copy to server
```bash
ssh-copy-id user@server
``` 

### SSH Agent
To set up SSH agent to avoid retyping passwords, you can do two things:

1. Add an ssh config file (will be absent by default)
```bash 
vi ~/.ssh/config
```
```
Host [hostname]
    User [username]
    IdentityFile ~/.ssh/[key]
```

2. Add the key when starting bash:
```bash
echo "ssh-add ~/.ssh/id_rsa &>/dev/null" >> .bashrc
```