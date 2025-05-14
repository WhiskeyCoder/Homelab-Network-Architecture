# 🏡 Homelab Network

Welcome to the documentation for my personal Homelab setup, a fully self-hosted, modular, automated, and constantly evolving digital command center. It supports my entertainment, research, development, business, and creative project needs. Designed for resilience, flexibility, and autonomy, this homelab is the heart of my technical playground and operational backbone.

🧰 **This repository serves as a real-world demonstration of my technical skill set.**  
It showcases my hands-on experience with:
- **Network architecture & segmentation (VLANs, routing, VPNs)**
- **Cybersecurity fundamentals (zero-trust, IDS/IPS, ad-blocking, DNS hardening)**
- **System administration (Proxmox, Docker, Linux, backup strategies)**
- **Self-hosted services & SaaS alternatives**
- **Automation and orchestration (n8n, Watchtower, Portainer stacks)**
- **DevOps and virtualization workflows**
- **Custom infrastructure for AI, and smart home tech**

Every node, service, and design choice in this homelab reflects intentional skill development — not just for fun, but as part of building a future-proof, resilient, and independent digital lifestyle.

---

## 🧠 Overview

This homelab serves five core purposes:

- **Entertainment & Media Hosting**  
- **Business and Development Server Infrastructure**  
- **Rapid OS Deployment & Virtual Lab Environments**  
- **Self-Hosted SaaS, API & Automation Projects**  
- **Experimental Pi Cluster for AI, OSINT, and Tactical Tools**

The system runs on a hybrid stack of Dell microservers, Raspberry Pi cluster, JBOD storage, Proxmox virtualization, and a fleet of open-source services for automation, media, development, and beyond.

---

## 🗺️ Network Architecture

<img src="https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/logical_network.png" alt="Homelab Network Map" width="100%">

> 📌 For full resolution: [Open Full Network Map](https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/logical_network.png)

---

## 🧱 Hardware Stack

- **Dell Microservers (x2)** – Virtualization (Proxmox), core workloads, and isolation
- **Intel NUC (x1)** – Dedicated self-hosted business system  
- **Custom JBOD Enclosure** – 40TB+ mass storage (media, datasets, and backups)  
- **Raspberry Pi Cluster (4 nodes)** – AI/ML training, SDR, OSINT, and microservices  
- **UPS Battery Backup** – Power protection for critical nodes  
- **ASUS ROG Router** – Firewall, DPI, segmentation, load balancing, WireGuard  
- **Unmanaged Switch** – Low-latency backbone connectivity  
- **Rackmount Enclosure** – Modular layout with airflow consideration  

---

## 🧱 Core Components

### 🧠 Purpose-Built Nodes

- **Entertainment Server** – Plex, SearXNG, AdGuard, Kavita, Romm, FreeTube, MeTube, Hoarder, and more
- **Business Server** – MongoDB, APIs, automation, dashboards, email systems, internal tools
- **Proxmox Lab** – OS testing and sandboxing: Windows, macOS, Kali, Android, Whonix, Linux variants
- **Dev PC** – Daily driver for AI model training, development work, and VS Code environments
- **Pi Cluster** – OSINT analysis, AI inference, SDR experimentation, Google Home alt
- **JBOD NAS** – OMV-hosted Docker volumes, file shares, and long-term storage

---

### 📶 Network Topology

- **ASUS ROG Router**
  - AI-powered firewall with IDS/IPS
  - VLAN-aware routing and segmentation
  - **VLAN 1** – Private Systems  
  - **VLAN 2** – Trusted Nodes & Core Services  
  - **VLAN 3** – IoT Devices  
  - **VLAN 4** – Guest Network  

- **Cloudflare Tunnel** – Zero Trust HTTPS access (no port forwarding)
- **WireGuard VPN** – Encrypted remote entry into LAN
- **Wi-Fi Segments**
  - Guest/IoT (2.4GHz / 5GHz)
  - Hidden SSID (6GHz) for Admin/Dev only

---

## 🧠 Smart Home Integration

> ⚙️ Fully local automation powered by Home Assistant

- Tapo Plugs, RGB Bulbs, Cleaning Bots
- Cameras, Doorbell, GoogleTV Projector
- LAN-only automation with dashboard tablet
- No external cloud dependencies for control

---

## ☁️ Cloud & Remote Services

- **Cloudflare Tunnel** – Domain + Zero Trust Access for:
  - Plex, Proxmox, APIs, Romm, Kavita, Wordpress, AudiobookShelf, etc.
- **Cloudflare Access** – Device-based policies, 2FA, secure HTTPS exposure

---

## 📽️ Entertainment Server Setup

#### ⚡ VPS/VPN VLAN (tunneled to VLAN 2)
- Overseerr, Sonarr, Radarr, Prowlarr, Bazarr, Lidar, Readarr, qBittorrent (*public domain only*)
- MeTube, FreeTube, Hoarder
- SearXNG – Private search engine

#### 🎬 VLAN 2 (Main Media Access)
- Plex – Public domain/original content
- AdGuard Home – Network-wide ad blocking
- LibreTranslate, LanguageTool – Replaces Google Translate & Grammarly
- Home Assistant – Local smart home control
- Mealie – Meal & recipe planner
- Firefly III – Self-hosted budgeting
- Watchtower – Auto Docker updates
- Immich – Google Photos alternative
- Excalidraw – Visual whiteboarding

#### 🔒 Cloudflare VLAN (tunneled to VLAN 2)
- Romm – DRM-free games (GOG)
- Kavita – Comics/eBooks (Humble Bundle only)
- AudiobookShelf – Because I prefer listening (thanks, dyslexia)
- Wordpress – Personal blog
- Manyfold – STL manager/sharing

---

## 👨‍💻 Dev & Business Stack

- Proxmox VE – Virtualization layer
- Docker SaaS stacks – Self-built APIs + services
- MongoDB – App database backend
- Monica – Relationship manager
- n8n – Workflow automation
- Gitea – Private Git repo hosting + version control
- Internal Docs, LMS, WP Sites

---

## 🔬 Pi Project Cluster

- Real-time intelligence/OSINT analysis
- AI/ML lightweight tasks + model serving
- SDR tools (signal capture, replay, mapping)
- Sensor simulation (air quality, environmental logs)

---

## 🖥️ Virtualization Lab (Proxmox)

- Windows 11 – Contract work
- Ubuntu – Linux development
- CentOS – For variety
- Kali – Cybersecurity projects
- Whonix – Onion-routing and privacy routing tests
- macOS – App testing
- Android – App development

---

## 🔐 Security Stack

- **No port forwarding**
- **WireGuard VPN** with client-level rules
- **Cloudflare Access** – SSO + 2FA + limited exposure
- **LAN segmentation via VLANs**
- **AdGuard + DNS hardening**
- **Snapshot + planned ZFS backups**

---

## 🛣️ Roadmap

- [ ] Grafana + Prometheus setup  
- [ ] Full ZFS snapshot/backup migration  
- [ ] Portainer stack auto-deploy documentation  
- [ ] CI/CD pipelines for hosted code  
- [ ] Publish Docker configs + secrets templates

---

## 📸 Photos

<img src="https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/physical_rack.png" alt="Rack Setup" width="30%">

> See `/images` for high-res physical rack shots and labeled diagrams.

---
## 🖨️ 3D-Printed Homelab Rack (DIY)
Inspired by a YouTube video showcasing a compact 10U Raspberry Pi network rack, I set out to design my own, without the $200 price tag. Using an open-source leg design as a base, I made several critical upgrades: redesigned handles and legs for durability, plus custom side struts for better structural integrity at scale. I’ve uploaded the core STL files on MakerWorld to help others get started. The rack is modular, stackable, and ideal for Raspberry Pi clusters or homelab expansions. You'll need M5 bolts (at least 51mm long); I used a $10 assorted hardware pack from Amazon.

### ✅ Project Highlights:
- Cost to print: $18 total (incl. 0.5kg of PLA+ and hardware)
- Design tools used: Tinkercad
- Open source: Mod-friendly STL files available on MakerWorld
- Future plans: I’ll be uploading accessory modules to extend the rack's capabilities

<img src="https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/stls.png" alt="Rack Setup" width="30%">

This custom build allowed me to maintain the flexibility and aesthetic of a pro-grade rack, without breaking the bank. 

### Can be downloaded from:
- The Network Rack Itself: [https://makerworld.com/en/models/604691-10-inch-network-rack-basics](https://makerworld.com/en/models/604691-10-inch-network-rack-basics)
- Custom Designed JBOD: [https://makerworld.com/en/models/669552-10-inch-jbod](https://makerworld.com/en/models/669552-10-inch-jbod)
- Intel Nuc 10 Inch rack Holder: [https://makerworld.com/en/models/708882-intel-nuc-10-inch-rack](https://makerworld.com/en/models/708882-intel-nuc-10-inch-rack)
- Hot Swapable Raspberry Pi Rack: [https://makerworld.com/en/models/604725-raspberry-pi-10-inch-rack-hot-swappable](https://makerworld.com/en/models/604725-raspberry-pi-10-inch-rack-hot-swappable)
---

## 🧙‍♂️ About Me

I’m Whiskey — a security professional, data analyst, tech entrepreneur, and chaos gremlin with a vision for self-hosted sovereignty. Every part of this lab was built on stubborn resilience, penny-pinching, and the refusal to depend on increasingly overpriced cloud systems.

---

## ⚠️ Legal Disclaimer

All services and configurations shared here are for **educational and personal reference only**.

- Plex, Sonarr, Radarr, Prowlarr, and qBittorrent are used *strictly* for **public domain and copyright-free media**.
- Romm hosts only **DRM-free games purchased legally through GOG**.
- Kavita hosts **comics and books obtained through Humble Bundle**.
- No piracy is promoted, facilitated, or tolerated.

---

## 🤝 Want to Collaborate?

- 💬 Always open to feedback, questions, or nerdy convos
- ⭐ Drop a star if this repo helped or inspired you
- 🛠️ Fork it, remix it, build on it — just give a shout!
