---
title: Webconfig
taxonomy:
    category:
        - docs
---

#### php-fpm
Settings:
```bash
cd /etc/php-fpm.d/
vi wiki.config
```

Restart php-fpm
```bash
systemctl restart php-fpm
```

#### Git sync settings
Plugins > Git Sync

#### Edit theme
```bash
cd webroot/user/theme/learn2-git-sync/css
vi custom.css
```