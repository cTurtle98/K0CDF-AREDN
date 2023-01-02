# K0CDF-AREDN

K0CDF Amateur Radio Emergency Data Network Infrastructure

This is the code that defines my infrastructure I host on the Amateur Radio Emergency Data Network

## Setup

these commands need to be run on the client computer running the ansible playbook

```bash
sudo apt install python3 python3-pip
pip3 install ansible proxmoxer
ansible-galaxy collection install community.general
ansible-galaxy collection install nginxinc.nginx_core
ansible-galaxy install wiggels.snipeit
```
