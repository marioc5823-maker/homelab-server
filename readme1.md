**Introduction:**

A personal homelab environment built and managed as production-grade 
infrastructure. This repository documents the full architecture, 
configuration, and automation behind a self-hosted private cloud running 
across 5 devices — managed entirely through Ansible for repeatable, 
version-controlled deployments.


**Architecture Overview:**

Device           | Hostname    | Main Role                  | OS              | CPU            | RAM       | Storage |
-----------------|-------------|----------------------------|-----------------|----------------|-----------|---------|
Desktop          | MariosPC    | Workstation/AnsibleControl | Ubuntu Desktop  | Ryzen 7 5700X  | 32GB DDR5 | 2TB     |
Home Server      | MariosLab   | Home Server                | Ubuntu Server   | Ryzen 5 2600   | 16GB DDR4 | 3.5TB   |
Raspberry Pi 3 B+| RPIGear2    | DNS/Network Manager        | Raspberry Pi OS | ARM Cortex-A53 | 1GB       | 16GB SD |
Raspberry Pi 3 B+| RPIGear3    |                            | Raspberry Pi OS | ARM Cortex-A53 | 1GB       | 16GB SD |
Raspberry Pi 4 B | RPIGear4    |                            | Raspberry Pi OS | ARM Cortex-A72 | 4GB       | 64GB SD |

**Services:**


**Tech Stack:**


**Lessons Learned:**

This project has overall helped me understand being in the positon of a system administrator. Since starting 
this project, my linux skills and management have 

Demo/Screenshots:
