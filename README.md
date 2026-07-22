# Home SOC Lab

A self-hosted Security Operations Center lab built on Proxmox VE, 
simulating enterprise network segmentation, DNS filtering, IDS, and 
(in progress) SIEM/threat detection.

## Hardware
- Dell OptiPlex 7010 | i5-3470 | 16GB RAM | Proxmox VE 9.2.2

## Network Architecture
<img width="626" height="813" alt="image" src="https://github.com/user-attachments/assets/9624b5ff-aa35-45be-a271-259e34eaaae2" />


## Stack
| Component | Purpose | Status |
|---|---|---|
| OPNsense | Firewall/Router | ✅ |
| Pi-hole | DNS filtering | ✅ |
| Kali Linux | Pentest platform | ✅ |
| Wazuh | SIEM | 🚧 in progress |
| Zeek | Network monitoring | ⬜ planned |
| T-Pot | Honeypot | ⬜ planned |
| The Hive | case management, sits alongside Wazuh | ⬜ planned |
| MISP | Database of Malware Info | ⬜ planned |

## Why I built this
I am building this SOC Home Lab to not only get experince building SOHO/Network Infrastructure but also step into the field of security!

## Issues and Fixes
https://docs.google.com/document/d/13sozdQZleyrlAooTkg3pj_kzX5qJ3pCORd70YGJuGdU/edit?usp=sharing
