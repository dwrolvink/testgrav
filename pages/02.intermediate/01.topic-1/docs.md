---
title: Permissions
taxonomy:
    category: docs
process:
	twig: true
---

#### Folder permissions
To set all the files and folders in a certain folder to a certain user:group, use the following:
```bash
chown -R user:group ./
```

#### Define groups
To add a user to a group, use the following:
```bash
usermod -aG additional_groups username
```
