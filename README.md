ASORC: Systems and Network Administration Infrastructure
Overview
This repository contains the comprehensive documentation and architectural layout for the deployment, configuration, and maintenance of network services and operating systems across heterogeneous environments, including Enterprise Linux, FreeBSD, and Windows Server.

1. Operating Systems Deployment and Provisioning
   Deployed, configured, and managed a wide array of operating systems, including Rocky Linux, Debian, openSUSE, Fedora, Linux Mint, Manjaro, Arch Linux, Gentoo, FreeBSD, GhostBSD, Haiku, and Windows Server 2025.  Handled      low-level disk partitioning and configured network interfaces, static/dynamic IP addressing, and package management systems utilizing native tools such as dnf, apt, zypper, pacman, and pkg.
   
2. Core Network Services and Storage Integration
   Remote Administration: Secured remote system access by deploying SSH with public key authentication, SCP, SFTP, VNC, and RDP protocols.
   Network Infrastructure: Implemented and managed local DNS resolution using BIND and dynamic IP allocation via DHCP services (KEA, isc-dhcp-server, and Windows DHCP).
   File Sharing: Configured NFS and Samba (SMB/CIFS) to ensure seamless and secure cross-platform file access.
   Block Storage: Deployed TrueNAS/FreeNAS to provision iSCSI targets, successfully integrating them with client initiators across multiple operating systems.
   Print Services: Configured CUPS print servers featuring automated virtual PDF backend generation for print job processing.
   
3. Advanced Security, Routing, and Monitoring
   Secure File Transfer: Deployed FTP services utilizing vsftpd, ProFTPd, and Windows FTP with strict user isolation and chroot jail environments.
   Traffic Control: Implemented Squid Proxy Cache with specific Access Control Lists (ACLs) and domain blacklisting for web traffic filtering.
   Network Security: Managed firewall configurations (firewalld), NAT routing, and VPN deployment to secure and segment network traffic.
   System Telemetry: Deployed continuous monitoring and alerting systems using Nagios Core (compiled from source), PRTG, and Netdata to track system health and service availability.
   Data Redundancy: Engineered fault-tolerant storage arrays by configuring RAID 5 using mdadm, ZFS (RAIDZ1), and Windows Storage functionalities.
   Disaster Recovery: Automated comprehensive backup strategies—including full, incremental, and mirrored backups—leveraging rsync, tar, and Windows Server Backup.

Detailed DocumentationAll detailed documentation, step-by-step implementation guides, configuration scripts, and system audit logs supporting this infrastructure are fully uploaded and available within this repository.
