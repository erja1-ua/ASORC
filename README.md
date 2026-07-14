🇪🇸 Español | [🇬🇧 English](./README.en.md)

# 🖥️ ASORC — Administración de Sistemas Operativos y Redes de Computadores

> Documentación técnica y memorias de prácticas: despliegue, configuración y mantenimiento de sistemas operativos y servicios de red en entornos heterogéneos (Linux, BSD y Windows Server).

![Status](https://img.shields.io/badge/status-completo-brightgreen)
![Docs](https://img.shields.io/badge/documentaci%C3%B3n-PDF-red)
![License](https://img.shields.io/badge/uso-acad%C3%A9mico-blue)

---

## 📌 Descripción

Este repositorio recoge las memorias completas de las prácticas de la asignatura **ASORC**. Cada práctica está documentada en detalle (PDF) con capturas, configuraciones y explicación paso a paso. Este README funciona como **índice rápido**: resume qué se ha hecho en cada bloque para que puedas localizar el contenido sin tener que abrir cada PDF.

---

## 📂 Índice

- [1. Despliegue y aprovisionamiento de sistemas operativos](#1-despliegue-y-aprovisionamiento-de-sistemas-operativos)
- [2. Servicios de red y almacenamiento](#2-servicios-de-red-y-almacenamiento-core)
- [3. Seguridad, enrutamiento y monitorización avanzada](#3-seguridad-enrutamiento-y-monitorización-avanzada)
- [Documentación detallada](#-documentación-detallada)

---

## 1. Despliegue y aprovisionamiento de sistemas operativos

Instalación, configuración y administración de un amplio abanico de sistemas operativos, incluyendo particionado de disco a bajo nivel, configuración de interfaces de red (IP estática/dinámica) y gestión de paquetes con las herramientas nativas de cada distribución.

| Sistema Operativo | Gestor de paquetes |
|---|---|
| Rocky Linux, Fedora | `dnf` |
| Debian, Linux Mint | `apt` |
| openSUSE | `zypper` |
| Manjaro, Arch Linux | `pacman` |
| Gentoo | `portage` |
| FreeBSD, GhostBSD | `pkg` |
| Haiku | — |
| Windows Server 2025 | — |

📄 **Memoria:** [`MEMORIA-PRACTICA1.pdf`](./MEMORIA-PRACTICA1.pdf)

---

## 2. Servicios de red y almacenamiento (core)

| Área | Tecnologías | Descripción |
|---|---|---|
| **Administración remota** | SSH (clave pública), SCP, SFTP, VNC, RDP | Acceso remoto seguro a los sistemas |
| **Infraestructura de red** | BIND (DNS), KEA / isc-dhcp-server / Windows DHCP | Resolución de nombres local y asignación dinámica de IP |
| **Compartición de archivos** | NFS, Samba (SMB/CIFS) | Acceso a ficheros multiplataforma |
| **Almacenamiento en bloque** | TrueNAS / FreeNAS (iSCSI) | Targets iSCSI integrados con iniciadores de distintos SO |
| **Impresión** | CUPS | Servidor de impresión con backend virtual a PDF |

📄 **Memoria:** [`MEMORIA-PRACTICA2.pdf`](./MEMORIA-PRACTICA2.pdf)

---

## 3. Seguridad, enrutamiento y monitorización avanzada

| Área | Tecnologías | Descripción |
|---|---|---|
| **Transferencia segura de ficheros** | vsftpd, ProFTPd, FTP (Windows) | Servidores FTP con aislamiento de usuarios (chroot) |
| **Control de tráfico** | Squid Proxy | Caché, ACLs y listas negras de dominios |
| **Seguridad de red** | firewalld, NAT, VPN | Segmentación y protección del tráfico |
| **Monitorización** | Nagios Core (compilado desde fuente), PRTG, Netdata | Telemetría y alertas de disponibilidad |
| **Redundancia de datos** | mdadm (RAID 5), ZFS (RAIDZ1), Windows Storage | Arrays tolerantes a fallos |
| **Recuperación ante desastres** | rsync, tar, Windows Server Backup | Backups completos, incrementales y en espejo |

📄 **Memoria:** [`MEMORIA-PRACTICA3.pdf`](./MEMORIA-PRACTICA3.pdf)

---

## 📚 Documentación detallada

Toda la documentación paso a paso, scripts de configuración y registros de auditoría del sistema están disponibles en los PDF de cada bloque, enlazados en las secciones anteriores.

