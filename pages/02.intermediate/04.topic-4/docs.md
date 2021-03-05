---
title: VNC
taxonomy:
    category: docs
---

## Remote management with VNC

See [this link](https://github.com/dwrolvink/Linux/blob/master/CentOS/setup_vnc.md) for CentOS. 
For Manjaro, see below.

### Source: 
- Install Remmina
  - Choose the VNC plugin, and optionally the RDP plugin too

### Target:
(Haven't got it working yet)
```
sudo pacman -S tigervnc-server
vncpasswd
sudo vi /etc/tigervnc/vncserver.users # add user binding
sudo cp /lib/systemd/system/vncserver@.service  /etc/systemd/system/vncserver@:1.service
sudo systemctl daemon-reload
sudo systemctl start vncserver@:1 # systemctl status vncserver@:1
sudo systemctl enable vncserver@:1
```
