**Introduction:**

A personal homelab environment built and managed as production-grade 
infrastructure. This repository documents the full architecture, 
configuration, and automation behind a self-hosted private cloud running 
across 5 node — managed entirely through Ansible.


**Architecture Overview:**

Device           | Hostname    | Main Role                  | OS              | CPU            | RAM       | Storage |
-----------------|-------------|----------------------------|-----------------|----------------|-----------|---------|
Desktop          | MariosPC    | Workstation/AnsibleControl | Ubuntu Desktop  | Ryzen 7 5700X  | 32GB DDR5 | 2TB     |
Home Server      | MariosLab   | Home Server                | Ubuntu Server   | Ryzen 5 2600   | 16GB DDR4 | 3.5TB   |
Raspberry Pi 3 B+| RPIGear2    | DNS/Network Manager        | Raspberry Pi OS | ARM Cortex-A53 | 1GB       | 16GB SD |
Raspberry Pi 3 B+| RPIGear3    |                            | Raspberry Pi OS | ARM Cortex-A53 | 1GB       | 16GB SD |
Raspberry Pi 4 B | RPIGear4    |                            | Raspberry Pi OS | ARM Cortex-A72 | 4GB       | 64GB SD |

**Services:**


-Pi-Hole
-Nextcloud
-PiVPN
-WireGuard
-Ansible
-Docker
-

**Tech Stack:**
| Category        | Technology                          |
|-----------------|-------------------------------------|
| Automation      | Ansible                             |
| OS (x86)        | Ubuntu Desktop 24.04, Ubuntu Server 24.04 |
| OS (ARM)        | Raspberry Pi OS (Bookworm)          |
| Hardware        | Ryzen x86 machines, Raspberry Pi 3B+ & 4B |
| DNS / Filtering | Pi-hole                             |
| VPN             | PiVPN (WireGuard)                   |
| Cloud Storage   | Nextcloud                           |
| Secret Mgmt     | Ansible Vault                       |
| Version Control | Git / GitHub                        |


**Lessons Learned:**


Demo/Screenshots:
