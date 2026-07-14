ENG:
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

ESP:
ASORC: Infraestructura de Administración de Sistemas y Redes
Descripción general
Este repositorio contiene la documentación técnica y el diseño de la arquitectura para el despliegue, configuración y mantenimiento de servicios de red y sistemas operativos en entornos heterogéneos, incluyendo Enterprise Linux, FreeBSD y Windows Server.
1. Despliegue y aprovisionamiento de sistemas operativos
   Implementación y administración de diversas distribuciones, incluyendo Rocky Linux, Debian, openSUSE, Fedora, Linux Mint, Manjaro, Arch Linux, Gentoo, FreeBSD, GhostBSD, Haiku y Windows Server 2025.  Gestión de            particionado de discos, configuración de interfaces de red, direccionamiento IP estático/dinámico y uso de gestores de paquetes nativos como dnf, apt, zypper, pacman y pkg.
   
2. Servicios de red e integración de almacenamiento
   Administración remota: Configuración de acceso seguro mediante SSH (autenticación por clave pública), SCP, SFTP, VNC y protocolos RDP.
   Servicios de red: Implementación de resolución de nombres mediante BIND (DNS) y asignación dinámica de direcciones IP vía DHCP (KEA, isc-dhcp-server y servicios Windows DHCP).
   Compartición de archivos: Integración de sistemas multiplataforma utilizando NFS y Samba (SMB/CIFS).
   Almacenamiento en bloque: Despliegue de TrueNAS/FreeNAS para el aprovisionamiento de destinos iSCSI e integración con clientes en distintos sistemas operativos.
   Servicios de impresión: Configuración de servidores de impresión CUPS con generación automatizada de archivos PDF como backend virtual.

3. Seguridad, enrutamiento y monitorización avanzada
   Transferencia de archivos segura: Despliegue de servicios FTP (vsftpd, ProFTPd, IIS FTP) con entornos de aislamiento (chroot jail) para usuarios restringidos.
   Control de tráfico: Configuración de Squid Proxy Cache con listas de control de acceso (ACLs) y filtrado de dominios para el control de navegación.
   Seguridad de red: Implementación de reglas de cortafuegos (firewalld), enrutamiento NAT y despliegue de soluciones VPN para la segmentación y protección del tráfico.
   Telemetría y control: Implementación de sistemas de monitorización mediante Nagios Core (compilado desde código fuente), PRTG y Netdata para la supervisión de salud y disponibilidad de servicios.
   Redundancia y alta disponibilidad: Configuración de almacenamiento tolerante a fallos mediante RAID 5 (mdadm), ZFS (RAIDZ1) y herramientas de gestión de discos de Windows.
   Recuperación ante desastres: Estrategias de backup automatizadas (totales, diferenciales e incrementales) usando rsync, tar y Windows Server Backup.

Documentación técnica
Toda la documentación técnica detallada, guías de implementación paso a paso, scripts de configuración y logs de auditoría del sistema que respaldan esta infraestructura se encuentran alojados y disponibles en este repositorio.
