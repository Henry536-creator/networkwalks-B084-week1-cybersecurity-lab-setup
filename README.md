<div align="center">

# Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2.6-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2025.4-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.2.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
</p>

---

## Project Overview

This project focuses on setting up a **virtual cybersecurity and penetration-testing laboratory** using VirtualBox and Kali Linux. The lab creates a controlled environment where you can safely and repeatedly use cybersecurity tools for network scanning, reconnaissance, vulnerability assessment, and other security-testing activities. The lab is configured on a private virtual network so you can add additional machines later and use them as targets for authorized security testing.

---

## Purpose
The purpose of this project is to establish a safe and controlled virtual cybersecurity lab environment using VirtualBox and Kali Linux. This environment will provide a platform for practising cybersecurity techniques, testing security tools, performing network analysis, and developing practical skills in ethical hacking and network security.

---

## Objectives

The main objectives I achieved in this project are to:
- Install and configure Oracle VirtualBox.
- Download and set up Kali Linux.
- Create and configure a NAT Network.
- Assign and configure the Kali Linux IP address.
- Test network connectivity.
- Create a virtual machine snapshot.
- Establish a functional environment for cybersecurity practical exercises.


## Tools Used
- Kali Linux 2025.4
- Oracle VirtualBox
- NAT Network

## Network Configuration

The following network configuration was identified on the Kali Linux virtual machine:

- Network Name: `NatNetwork`
- Network type: `Nat Network`
- Network Subnet: `10.0.2.0/24`
- Default Gateway: `10.0.2.1`
- Kali IP: `10.0.2.15/24`

---

## Network Verification

The network configuration was checked using Linux terminal commands.

Command used:
ip route

Observed output:
default via 10.0.2.1 dev eth0 proto dhcp src 10.0.2.15 metric 100
10.0.2.0/24 dev eth0 proto kernel scope link src 10.0.2.15 metric 100

This confirmed the default gateway, network subnet, and assigned IP address of the Kali Linux virtual machine.

---

## Tasks Completed
- Configured the VirtualBox NAT Network.
- Configured Kali Linux networking.
- Tested internet connectivity and DNS resolution.
- Enabled clipboard and drag-and-drop.
- Configured a shared folder.
- Created a VM snapshot.

---

## Screenshot and Evidences

The evidence includes:

### 1 Oracle VirtualBox interface.
![VirtualBox-Manager](vm.png)

### 2 Kali Linux Desktop Environment.
![Kali Linux Desktop](kali-desktop.png)

### 3 VirtualBox network configuration.
![NAT network Configuration](NAT-configuration.png)

### 4 NAT adapters 
![Nat adapters](NAT-adapters.png)

### 5 Internet configuration
![internet-config](internet-confip.png)

### 6 Virtual machine snapshot.
![vm snapshots](vm-snapshots.png)

##  Conclusion

The cybersecurity lab environment was established using Oracle VirtualBox and Kali Linux. The setup provides a controlled virtual environment for practising cybersecurity techniques, conducting network analysis, and exploring penetration-testing tools.

This environment serves as a foundation for future hands-on cybersecurity exercises, network security assessments, and practical ethical hacking activities.
