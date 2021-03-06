---
title: 'Installing docker'
taxonomy:
    category:
        - docs
visible: true
---

# Manjaro
```
sudo pacman -S docker docker-compose
sudo systemctl start docker
sudo systemctl enable docker
sudo usermod -aG docker dorus 
sudo systemctl start reboot.target
```