# Satomi Sugiue — IT Portfolio

## About Me
IT infrastructure student based in Canada.
I learn best by doing, and I enjoy making complex systems visually clear.
Currently looking for Helpdesk / Tier 1 IT support roles.

## Projects

### Capstone Project — Enterprise Network Infrastructure (2026)
Built a full enterprise-level network environment using only virtual machines on a physical PC.

**Technologies used:**
- Hyper-V (Windows Server 2025)
- pfSense (Firewall / WAN-LAN routing)
- Active Directory / Domain Controller
- DHCP Server (Ubuntu Linux)
- iSCSI / vSAN / Live Migration
- Windows Server Core 2025

**What I built:**
- Designed network diagram and IP address table from scratch
- Configured pfSense firewall with DNS resolver and block lists
- Set up Active Directory domain with domain-joined clients
- Configured iSCSI storage and Hyper-V cluster with Live Migration
- Documented 190+ pages of step-by-step configuration and troubleshooting

**Demo Video:**
[Watch the network infrastructure test on YouTube](https://youtu.be/_P3HYmrGIL4)

**What I learned:**
- How enterprise infrastructure is structured and connected
- Troubleshooting under pressure (rebuilt the entire environment from scratch after hardware failure)
- The importance of following diagrams top-to-bottom and keeping detailed notes

## Skills
- Windows Server / Windows Core
- Linux (Ubuntu)
- Networking (TCP/IP, DNS, DHCP, Firewall)
- Virtualization (Hyper-V)
- Active Directory
- Troubleshooting & Documentation


### Multi-Site Domain Project (2026)
Built a simulated multi-site enterprise network connecting two geographically separated offices (Vancouver and Toronto) using virtualization.

**Technologies used:**
- Hyper-V (Windows Server 2025)
- pfSense (IPsec VPN Tunnel between sites)
- Active Directory Domain Services (multi-site replication)
- DNS (Forward & Reverse Lookup Zones)
- RRAS (Routing and Remote Access)
- AD Sites and Services (site link configuration)
- Group Policy (GPO replication test)

**What I built:**
- Designed a two-site network with IPsec VPN tunnel over a simulated WAN
- Configured pfSense firewalls at both sites with IKEv2 authentication
- Set up Active Directory replication between Vancouver and Toronto DCs
- Verified replication of users, DNS A records, and GPOs across sites
- Documented all configurations and test results (75 pages)

**What I learned:**
- How multi-site AD replication works across a WAN link
- IPsec VPN tunnel configuration using both pfSense and Windows RRAS
- AD Sites and Services subnet and site link configuration
