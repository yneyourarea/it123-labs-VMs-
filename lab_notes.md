# Week 2 – Installing and Configuring Windows & Linux Virtual Machines

## Windows Server Installation
- Created VM: `Windows_Server`
- OS Type: Microsoft Windows → Version: Windows Server 2019/2022 (64-bit)
- RAM: 4096 MB
- CPU: 2 Cores
- Storage: 50 GB (VDI, dynamically allocated)
- Attached ISO: Windows Server ISO
- Installed OS with:
  - Username: Admin
  - Password: P@ssw0rd123
- Networking: NAT (or Bridged, depending on setup)
- Snapshot created: `Clean Install – Windows Server`

## Ubuntu Server Installation
- Created VM: `Ubuntu_Server`
- OS Type: Linux → Version: Ubuntu (64-bit)
- RAM: 2048 MB
- CPU: 2 Cores
- Storage: 30 GB (VDI, dynamically allocated)
- Attached ISO: Ubuntu 22.04 Server ISO
- Installed OS with:
  - Username: admin
  - Password: P@ssw0rd123
- Installed OpenSSH Server
- Networking: NAT (or Bridged, depending on setup)
- Snapshot created: `Clean Install – Ubuntu Server`

## Summary of VM Configurations

| VM Name         | OS Installed            | RAM   | CPU | Storage | Network Mode | Notes                          |
|-----------------|-------------------------|-------|-----|---------|--------------|--------------------------------|
| Windows_Server  | Windows Server 2019/22  | 4 GB  | 2   | 50 GB   | NAT/Bridged  | Snapshot: Clean Install        |
| Ubuntu_Server   | Ubuntu Server 22.04 LTS | 2 GB  | 2   | 30 GB   | NAT/Bridged  | SSH enabled, Snapshot taken    |

## GitHub Update
- Files stored in `Week2/`:
  - `lab_notes.md`
  - `vm.png`
  - `windows.png`
  - `ubuntu.png`
- Commands used:
  ```bash
  git add .
  git commit -m "Week 2 – Windows & Ubuntu Server installation"
  git push origin main
