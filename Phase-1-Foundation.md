# Phase 1: Operating Systems & Initial Setup

## Objective
Set up a basic IT lab environment using virtual machines and learn fundamental operating system tasks.

---

## VM Setup

### Ubuntu Server
- Version: Ubuntu Server 22.04 LTS
- Platform: Hyper-V Gen 2
- Username: zack
- Resources: 2–4 GB RAM, 2 CPU cores
- Network: Default Switch (NAT)
- OpenSSH installed for remote access
- Snapshot created: "Clean Baseline"

### Windows VM (Planned / In Progress)
- Purpose: Practice Windows-based IT support tasks
- Will include:
  - User account management
  - File system navigation
  - Software installation and troubleshooting

---

## Basic Tasks Completed

### System Updates
```bash
sudo apt update && sudo apt upgrade -y
