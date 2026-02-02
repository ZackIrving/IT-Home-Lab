# Phase 1: Foundation

## VM Setup
- Ubuntu Server 22.04 LTS (Hyper-V Gen 2)
- Username: zack
- Memory: 2–4 GB, 2 CPU cores
- Network: Default Switch (NAT)
- OpenSSH installed for remote access
- Snapshot taken: 'Phase 1 - Clean Baseline'

## Core Tools Installed
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y net-tools curl wget ufw htop unzip jq rsyslog auditd
