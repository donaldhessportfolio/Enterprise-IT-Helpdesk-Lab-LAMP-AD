<h1 align="center">Enterprise-IT-Helpdesk-Lab-LAMP-AD</h1>

<p align="center">
Enterprise help desk simulation lab featuring Active Directory, a full LAMP stack, and osTicket ticketing workflows.
</p>

<p align="center">
  <img src="docs/banner.jpg" width="900"/>
</p>

---

## Executive Summary
This project simulates a small enterprise help desk environment backed by Active Directory and a Linux-hosted osTicket deployment on a full LAMP stack (Linux, Apache, MariaDB, PHP). The lab demonstrates identity management, infrastructure deployment, service validation, and real-world help desk tooling in an end-to-end environment.

---

## Architecture
<p align="center">
  <img src="docs/architecture-diagram.png" width="600"/>
</p>

**Core components**
- **Windows Server 2022 (AD DS)** — Identity provider, OU structure, automated provisioning
- **Ubuntu Server (LAMP)** — Apache + PHP frontend with MariaDB backend
- **osTicket** — Web-based help desk platform
- **Admin / Client Systems** — Browser access + SSH administration
- **Lab Network** — Isolated VMware-based enterprise-style subnet

---

## Table of Contents
- [Executive Summary](#executive-summary)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Build Phases](#build-phases)
  - [Phase 1 — Active Directory Foundation](#phase-1--active-directory-foundation)
  - [Phase 2 — LAMP Stack Deployment](#phase-2--lamp-stack-deployment)
  - [Phase 3 — osTicket Deployment](#phase-3--osticket-deployment)
- [Deployment Walkthrough](#deployment-walkthrough)
- [Lessons Learned](#lessons-learned)
- [Roadmap](#roadmap)

---

## Tech Stack
- **Windows Server 2022** (Active Directory Domain Services)
- **Ubuntu Server** (Linux LAMP stack)
- **Apache** (Web layer)
- **MariaDB** (Database layer)
- **PHP** (Application runtime)
- **osTicket** (Help desk platform)

---

## Build Phases
