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

**Network Diagram:**
<img width="803" height="652" alt="スクリーンショット 2026-04-30 午後1 44 53" src="https://github.com/user-attachments/assets/32810066-7eec-46d4-97b8-882ab5792a3f" />
<img width="800" height="419" alt="スクリーンショット 2026-04-30 午後1 45 04" src="https://github.com/user-attachments/assets/b173261d-cc62-4078-8c2a-1518d8918d86" />

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


--------------------------------------------------------------
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

**Network Diagram:**
<img width="726" height="286" alt="スクリーンショット 2026-04-30 午後1 44 31" src="https://github.com/user-attachments/assets/528a9be5-ff49-41b8-a1a4-52d18e6322cd" />

**What I learned:**
- How multi-site AD replication works across a WAN link
- IPsec VPN tunnel configuration using both pfSense and Windows RRAS
- AD Sites and Services subnet and site link configuration

----------------------------------------------------------------
### CentOS 7 — Two Mail Server Configuration (2025)
Built a fully functional two-server mail system on CentOS 7 using virtual machines, with pfSense as the NAT router/gateway.

**Technologies used:**
CentOS 7 (x2 virtual machines)
Postfix (SMTP server)
Dovecot (IMAP / POP3)
SquirrelMail + Apache (Webmail)
pfSense (Firewall / Router)
Thunderbird (Mail client)
Wireshark / tshark (Network traffic analysis)

**What I built:**
Configured two mail servers with separate domains (mail.tsplab.com / mail2.tsplab.com)
Set up pfSense DNS resolver with MX records and static DHCP mappings
Configured Postfix with Gmail relay (SASL authentication, TLS, port 587)
Installed and configured Dovecot for IMAP (port 143) and POP3 (port 110)
Installed SquirrelMail on Apache for browser-based webmail access
Verified email delivery across both servers using telnet and Thunderbird
Captured live SMTP traffic between servers using tshark

**Network Diagram:**
<img width="805" height="572" alt="スクリーンショット 2026-04-30 午後2 05 03" src="https://github.com/user-attachments/assets/567cb78c-73ba-49c9-878c-ddf6e4631240" />

**Demo Video:**
Watch mail sent between 2 domains
https://drive.google.com/file/d/1bK2HzKV_nOraDDUuZ0-t9Phd2wyj9qHU/view?usp=share_link

**What I learned:**
How SMTP, IMAP, and POP3 work at the protocol level (tested manually via telnet)
How pfSense DNS resolver handles internal MX records
Debugging mail delivery issues using logs and queue inspection


## Skills
Windows Server / Windows Core
Linux (CentOS, Ubuntu)
Networking (TCP/IP, DNS, DHCP, SMTP, IMAP, POP3, Firewall)
Virtualization (Hyper-V, VirtualBox)
Active Directory
Troubleshooting & Documentation
