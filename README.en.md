[🇪🇸 Español](./README.md) | 🇬🇧 English

# 🖥️ ASORC — Operating Systems and Computer Network Administration

> Technical documentation and lab reports: deployment, configuration, and maintenance of operating systems and network services across heterogeneous environments (Linux, BSD, and Windows Server).

![Status](https://img.shields.io/badge/status-complete-brightgreen)
![Docs](https://img.shields.io/badge/documentation-PDF-red)
![License](https://img.shields.io/badge/use-academic-blue)

---

## 📌 Overview

This repository contains the full lab reports for the **ASORC** (Operating Systems and Computer Network Administration) course. Each lab is documented in detail (PDF) with screenshots, configurations, and step-by-step explanations. This README serves as a **quick-reference index**: it summarizes what was done in each block so you can locate content without opening every PDF.

---

## 📂 Table of Contents

- [1. Operating System Deployment and Provisioning](#1-operating-system-deployment-and-provisioning)
- [2. Core Network Services and Storage](#2-core-network-services-and-storage)
- [3. Advanced Security, Routing, and Monitoring](#3-advanced-security-routing-and-monitoring)
- [Detailed Documentation](#-detailed-documentation)

---

## 1. Operating System Deployment and Provisioning

Installation, configuration, and administration of a wide range of operating systems, including low-level disk partitioning, network interface configuration (static/dynamic IP), and package management using each distribution's native tools.

| Operating System | Package Manager |
|---|---|
| Rocky Linux, Fedora | `dnf` |
| Debian, Linux Mint | `apt` |
| openSUSE | `zypper` |
| Manjaro, Arch Linux | `pacman` |
| Gentoo | `portage` |
| FreeBSD, GhostBSD | `pkg` |
| Haiku | — |
| Windows Server 2025 | — |

📄 **Report:** [`MEMORIA-PRACTICA1.pdf`](./MEMORIA-PRACTICA1.pdf)

---

## 2. Core Network Services and Storage

| Area | Technologies | Description |
|---|---|---|
| **Remote Administration** | SSH (public key auth), SCP, SFTP, VNC, RDP | Secure remote access to systems |
| **Network Infrastructure** | BIND (DNS), KEA / isc-dhcp-server / Windows DHCP | Local name resolution and dynamic IP allocation |
| **File Sharing** | NFS, Samba (SMB/CIFS) | Cross-platform file access |
| **Block Storage** | TrueNAS / FreeNAS (iSCSI) | iSCSI targets integrated with initiators across multiple OSes |
| **Printing** | CUPS | Print server with virtual PDF backend |

📄 **Report:** [`MEMORIA-PRACTICA2.pdf`](./MEMORIA-PRACTICA2.pdf)

---

## 3. Advanced Security, Routing, and Monitoring

| Area | Technologies | Description |
|---|---|---|
| **Secure File Transfer** | vsftpd, ProFTPd, Windows FTP | FTP servers with user isolation (chroot jails) |
| **Traffic Control** | Squid Proxy | Caching, ACLs, and domain blacklisting |
| **Network Security** | firewalld, NAT, VPN | Traffic segmentation and protection |
| **Monitoring** | Nagios Core (built from source), PRTG, Netdata | System telemetry and availability alerting |
| **Data Redundancy** | mdadm (RAID 5), ZFS (RAIDZ1), Windows Storage | Fault-tolerant storage arrays |
| **Disaster Recovery** | rsync, tar, Windows Server Backup | Full, incremental, and mirrored backups |

📄 **Report:** [`MEMORIA-PRACTICA3.pdf`](./MEMORIA-PRACTICA3.pdf)

---

## 📚 Detailed Documentation

All step-by-step documentation, configuration scripts, and system audit logs are available in the PDF reports linked in each section above.

