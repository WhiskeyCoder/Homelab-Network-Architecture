# 🏡 Homelab Network - Private Datacenter

Welcome to the documentation for my personal **Private Datacenter** — a fully self-hosted, enterprise-grade infrastructure that rivals commercial hosting providers. This isn't just a homelab; it's a **production-scale digital command center** providing critical services to households, businesses, and organizations while maintaining complete data sovereignty and operational independence.

🧰 **This repository demonstrates enterprise-level technical expertise in action.**  
It showcases real-world experience with:
- **Enterprise network architecture & advanced segmentation (VLANs, routing, multi-site VPNs)**
- **Production cybersecurity implementation (zero-trust, IDS/IPS, threat detection, DNS hardening)**
- **Scalable system administration (Proxmox clustering, container orchestration, Linux hardening)**
- **Commercial-grade service hosting & SaaS platform development**
- **Advanced automation and orchestration (n8n workflows, CI/CD pipelines, infrastructure as code)**
- **Private cloud infrastructure for AI/ML workloads and data analytics**
- **High-availability storage systems with disaster recovery**
- **Multi-tenant hosting environment with client isolation**

Every component in this private datacenter reflects **production-ready infrastructure design** — built for resilience, scalability, security, and 24/7 operational requirements that serve real clients and critical business functions.

---

## 🏢 Datacenter Services Overview

This private infrastructure provides **enterprise-grade hosting services** across multiple domains:

### 🏥 **Commercial Client Hosting**
- **Private Ambulance Service** - Full WordPress hosting with 99.9% uptime SLA
- **Multiple Business Websites** - Static and dynamic hosting with SSL termination
- **E-commerce Platforms** - Secure transaction processing and PCI compliance considerations

### 🤖 **Private AI & Analytics Infrastructure**
- **Completely Air-Gapped AI System** - No external dependencies or data exposure
- **Custom ML Pipeline** - Data ingestion, processing, model training, and inference
- **Private Large Language Models** - Self-hosted alternatives to ChatGPT/GPT-4
- **Analytics Dashboard** - Real-time business intelligence and data visualization

### 🏠 **Residential & Family Services**
- **Multi-household Network Services** - VPN, DNS, ad-blocking for extended family
- **Private Cloud Storage** - Secure file sharing and collaboration platforms  
- **Entertainment Streaming** - High-definition media serving with content management
- **Smart Home Orchestration** - Centralized automation across multiple properties

### 💼 **SaaS Platform Development**
- **Custom API Development** - Python Flask microservices architecture
- **Database-as-a-Service** - MongoDB clusters with automated backup/recovery
- **Workflow Automation** - n8n-powered business process automation
- **Development Environment Provisioning** - On-demand VM/container deployment

---

## 🧠 Infrastructure Overview

This datacenter supports **five operational tiers**:

- **🏢 Commercial Hosting & Business Services**  
- **🤖 Private AI & Data Analytics Infrastructure**  
- **🎯 Rapid Development & Testing Environments**  
- **☁️ Self-Hosted SaaS Platform & API Services**  
- **🔬 Research Cluster for AI/ML, OSINT, and Security Tools**

The system operates on a **hybrid cloud architecture** combining bare-metal servers, virtualization clusters, distributed storage, and container orchestration — all designed for **enterprise-level reliability and performance**.

---

## 🗺️ Network Architecture

<img src="https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/logical_network.png" alt="Homelab Network Map" width="100%">

> 📌 For full resolution: [Open Full Network Map](https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/logical_network.png)

---

## 🏗️ Enterprise Hardware Stack

### **Primary Compute Infrastructure**
- **Dell Microservers (x2)** – Proxmox clustering, high-availability virtualization
- **Intel NUC Business Node** – Dedicated client hosting with isolated workloads  
- **Raspberry Pi Compute Cluster (4 nodes)** – Distributed AI inference and microservices

### **Enterprise Storage Architecture**
- **Hot Storage Tier** – NVMe SSDs for database workloads and active applications
- **Warm Storage Tier** – High-performance HDDs for content delivery and file services  
- **Cold Storage Tier** – 40TB+ archival storage with automated lifecycle management
- **Custom JBOD Enclosure** – Redundant storage with RAID configurations
- **Distributed Backup System** – Multi-site replication and disaster recovery

### **Network & Infrastructure**
- **ASUS ROG Enterprise Router** – Advanced firewall, DPI, load balancing, SD-WAN
- **Managed Switch Infrastructure** – VLAN isolation and QoS for production workloads
- **UPS & Power Management** – Uninterruptible power with graceful shutdown automation
- **Environmental Monitoring** – Temperature, humidity, and power consumption tracking
- **Custom 3D-Printed Rack System** – Modular, scalable 10U infrastructure housing

---

## 🏢 Commercial Hosting Services

### **Web Hosting Platform**
- **WordPress Hosting** – Managed hosting for multiple business clients
  - **Private Ambulance Service** – Mission-critical healthcare provider website
  - **Professional Services** – Attorney, consultant, and contractor websites
  - **Small Business Portfolios** – Restaurant, retail, and service company sites

- **Static Site Hosting** – High-performance static content delivery
  - **JAMstack Applications** – React, Vue, and Angular SPA hosting
  - **Portfolio & Documentation Sites** – Professional presence for freelancers
  - **Landing Pages** – Marketing and conversion-optimized sites

### **SaaS Platform Infrastructure**
- **Custom API Development** – Python Flask microservices for business automation
  - **CRM Integration APIs** – Customer data synchronization and management
  - **Payment Processing** – Secure transaction handling and e-commerce support
  - **Inventory Management** – Real-time stock tracking and order fulfillment
  - **Appointment Scheduling** – Healthcare and service provider booking systems

- **Database-as-a-Service** – MongoDB clusters with automated scaling
- **Authentication & Authorization** – OAuth2/SAML integration for enterprise clients
- **Monitoring & Analytics** – Real-time performance metrics and business intelligence

---

## 🤖 Private AI & Analytics Infrastructure

### **Completely Isolated AI System**
> **Zero external dependencies** - All AI processing occurs on local infrastructure

- **Private Language Models** – Self-hosted alternatives to commercial AI services
  - **Llama 2/3 Deployment** – Fine-tuned models for specific business domains
  - **Code Generation** – Private GitHub Copilot alternative for development teams
  - **Document Analysis** – PDF/text processing without cloud exposure

- **Custom ML Pipeline**
  - **Data Ingestion** – Automated collection from multiple business sources
  - **Feature Engineering** – Custom preprocessing for domain-specific models
  - **Model Training** – Distributed training across Pi cluster and main servers
  - **Inference Serving** – Real-time prediction APIs with sub-100ms latency

- **Analytics Dashboard** – Self-built business intelligence platform
  - **Real-time Metrics** – Live performance monitoring for hosted services
  - **Predictive Analytics** – Forecasting and trend analysis for business clients
  - **Custom Reporting** – Automated report generation and distribution

---

## 🌐 Network Topology & Security

### **Advanced Network Segmentation**
- **ASUS ROG Router** with AI-powered threat detection
  - **VLAN 1** – Production hosting environment (isolated)
  - **VLAN 2** – Internal services and development  
  - **VLAN 3** – IoT and smart home devices
  - **VLAN 4** – Guest network with restricted access
  - **VLAN 5** – AI/ML cluster (air-gapped)

### **Zero-Trust Security Architecture**
- **Cloudflare Tunnel** – Secure HTTPS without port forwarding
- **WireGuard VPN** – Encrypted site-to-site and remote access
- **Multi-factor Authentication** – Hardware tokens and biometric verification
- **Certificate Management** – Automated SSL/TLS with Let's Encrypt
- **Intrusion Detection** – Real-time monitoring and automated response

---

## 💾 Enterprise Storage Systems

### **Tiered Storage Architecture**
```
📊 Hot Tier (NVMe SSD)
├── Database clusters (MongoDB, PostgreSQL)
├── Active websites and applications  
└── Container image registry

🗄️ Warm Tier (High-Performance HDD)  
├── Media content delivery
├── File sharing and collaboration
└── Development environments

❄️ Cold Tier (Archival Storage)
├── Backup and disaster recovery
├── Long-term data retention
└── Compliance and audit logs
```

### **Data Protection & Recovery**
- **RAID Configurations** – Hardware and software RAID across storage tiers
- **Automated Backups** – Hourly snapshots, daily offsite replication
- **Disaster Recovery** – Multi-site backup with rapid restore capabilities
- **Data Integrity** – Checksums and corruption detection across all storage

---

## 📽️ Entertainment & Media Services

#### ⚡ Content Acquisition Pipeline (VLAN - Tunneled)
- **Overseerr** – Content request and approval workflow
- **Sonarr/Radarr/Lidarr** – Automated media management (*public domain only*)
- **Prowlarr/Bazarr** – Indexer management and subtitle automation
- **qBittorrent** – P2P client for legal, open-source content
- **MeTube/FreeTube** – YouTube content archival and ad-free viewing

#### 🎬 Core Media Platform (VLAN 2)
- **Plex Media Server** – 4K streaming with hardware transcoding
- **Jellyfin** – Open-source streaming alternative with mobile apps
- **Romm** – DRM-free game library (GOG purchases)
- **Kavita** – Digital comics and ebook management
- **AudiobookShelf** – Personal audiobook streaming service

#### 🔧 Supporting Services
- **AdGuard Home** – Network-wide ad blocking and DNS filtering
- **SearXNG** – Private search engine aggregation
- **LibreTranslate** – Self-hosted translation service
- **Immich** – Google Photos replacement with AI photo organization

---

## 👨‍💻 Development & DevOps Platform

### **Development Infrastructure**
- **Gitea** – Private Git repository hosting with CI/CD
- **Docker Registry** – Private container image storage and distribution
- **Portainer** – Container orchestration and management interface
- **Watchtower** – Automated container updates and security patching

### **Testing & Staging Environments**
- **Proxmox VE Cluster** – On-demand VM provisioning for testing
  - **Windows 11** – Client application testing and development
  - **Ubuntu/CentOS** – Linux server application deployment
  - **Kali Linux** – Security testing and penetration testing
  - **macOS** – Cross-platform application compatibility
  - **Android-x86** – Mobile application development and testing

### **Business Applications**
- **Monica CRM** – Customer relationship management
- **Firefly III** – Financial management and budgeting
- **n8n** – Workflow automation and business process integration
- **Mealie** – Recipe management and meal planning

---

## 🔬 Research & Development Cluster

### **Raspberry Pi Compute Cluster**
- **Distributed AI Training** – Federated learning across multiple nodes
- **OSINT Analysis Platform** – Open-source intelligence gathering and analysis
- **Software Defined Radio** – Signal capture, analysis, and replay
- **IoT Development** – Sensor networks and edge computing research
- **Cryptocurrency Node** – Blockchain validation and development testing

### **Security Research Lab**
- **Vulnerability Assessment** – Automated security scanning and reporting
- **Malware Analysis** – Isolated environment for threat research
- **Network Forensics** – Traffic analysis and incident response
- **Compliance Testing** – GDPR, HIPAA, and industry standard validation

---

## 🔐 Enterprise Security Implementation

### **Multi-layered Security Architecture**
- **Perimeter Security** – Advanced firewall with geo-blocking and DPI
- **Network Segmentation** – Micro-segmentation with VLAN isolation
- **Identity Management** – Centralized authentication with LDAP integration
- **Data Encryption** – End-to-end encryption for data at rest and in transit
- **Monitoring & SIEM** – Real-time threat detection and incident response

### **Compliance & Governance**
- **Data Retention Policies** – Automated lifecycle management
- **Audit Logging** – Comprehensive activity tracking across all systems
- **Access Controls** – Role-based permissions with principle of least privilege
- **Incident Response** – Documented procedures and automated remediation

---

## 📊 Monitoring & Observability

### **Infrastructure Monitoring**
- **Prometheus** – Metrics collection and time-series database
- **Grafana** – Real-time dashboards and alerting
- **Uptime Kuma** – Service availability monitoring with notifications
- **Netdata** – System performance monitoring with sub-second granularity

### **Application Performance Monitoring**
- **Custom Metrics** – Business KPIs and application-specific monitoring
- **Log Aggregation** – Centralized logging with search and analysis
- **Distributed Tracing** – Request tracking across microservices
- **Capacity Planning** – Resource utilization forecasting and scaling

---

## 🛣️ Datacenter Roadmap

### **Short-term Enhancements**
- [ ] **Kubernetes Deployment** – Container orchestration for improved scalability
- [ ] **GitLab CI/CD Migration** – Enhanced DevOps pipeline automation  
- [ ] **Ceph Storage Cluster** – Distributed storage with automatic replication
- [ ] **Advanced Threat Detection** – AI-powered security analytics

### **Medium-term Expansion**  
- [ ] **Multi-site Replication** – Disaster recovery with geographic distribution
- [ ] **Edge Computing Nodes** – Distributed computing for reduced latency
- [ ] **Advanced AI Capabilities** – Computer vision and natural language processing
- [ ] **Blockchain Infrastructure** – Cryptocurrency and smart contract development

### **Long-term Vision**
- [ ] **Fully Automated Infrastructure** – Self-healing and self-scaling systems
- [ ] **Commercial Datacenter Services** – Expand to serve additional business clients
- [ ] **Research Partnerships** – Collaboration with universities and research institutions
- [ ] **Open Source Contributions** – Share infrastructure templates and automation tools

---

## 📸 Physical Infrastructure

<img src="https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/physical_rack.png" alt="Rack Setup" width="30%">

> See `/images` for high-resolution physical infrastructure photos and detailed component diagrams.

---

## 🖨️ Custom 3D-Printed Infrastructure (DIY Engineering)

Recognizing the need for professional-grade rack mounting without enterprise pricing, I engineered a **completely custom 10U network rack system**. Starting with open-source components, I redesigned critical structural elements for enhanced durability and scalability:

### ✅ **Engineering Improvements:**
- **Reinforced load-bearing design** – Supports full server equipment weight
- **Modular expansion capability** – Stackable units for datacenter growth
- **Integrated cable management** – Professional routing and organization
- **Cost optimization** – Total build cost: $18 vs $200+ commercial alternatives

### 📐 **Technical Specifications:**
- **Design Software:** Tinkercad with custom parametric modeling
- **Materials:** PLA+ filament with M5 stainless steel hardware
- **Load Capacity:** 50+ lbs per rack unit with proper weight distribution
- **Dimensions:** Standard 10" depth, 19" width compatibility

<img src="https://github.com/WhiskeyCoder/Homelab-Network-Architecture/blob/main/images/stls.png" alt="Custom Rack Components" width="30%">

### 🔗 **Open Source Hardware Designs:**
All rack components are freely available for community use and modification:

- **Network Rack Framework:** [10-inch Network Rack Basics](https://makerworld.com/en/models/604691-10-inch-network-rack-basics)
- **Custom JBOD Enclosure:** [10-inch JBOD Storage Mount](https://makerworld.com/en/models/669552-10-inch-jbod)  
- **Intel NUC Mount:** [Intel NUC 10-inch Rack Adapter](https://makerworld.com/en/models/708882-intel-nuc-10-inch-rack)
- **Hot-Swappable Pi Cluster:** [Raspberry Pi Rack Mount System](https://makerworld.com/en/models/604725-raspberry-pi-10-inch-rack-hot-swappable)

This custom infrastructure demonstrates **practical engineering problem-solving** and **cost-effective innovation** — core skills essential for scalable technology implementation.

---

## 🧙‍♂️ About the Engineer

I'm **Whiskey** — a cybersecurity professional, data analyst, and technology entrepreneur with a passion for **digital sovereignty and infrastructure independence**. This private datacenter represents years of intentional skill development in enterprise technologies, built through persistence, innovation, and a refusal to accept vendor lock-in or cloud dependency.

### **Professional Expertise Demonstrated:**
- **Enterprise Infrastructure Design** – Scalable, resilient system architecture
- **Commercial Service Delivery** – Real client hosting with SLA commitments  
- **Security Implementation** – Zero-trust networking and threat detection
- **Automation & DevOps** – CI/CD pipelines and infrastructure as code
- **Cost Optimization** – Maximum capability with minimal budget through innovation

**This homelab is more than a hobby — it's a** ***professional-grade demonstration*** **of enterprise technology skills applied in a real-world, production environment.**

---

## ⚠️ Legal & Compliance Notice

All services and infrastructure documented here operate under **strict legal and ethical guidelines**:

### **Content & Copyright Compliance:**
- **Media Services** utilize only **public domain, creative commons, and legally purchased content**
- **Software Deployment** exclusively uses **open-source or properly licensed software**
- **Client Data Protection** maintains **GDPR compliance and privacy by design**

### **Commercial Services:**
- All **business hosting services** operate under **proper service agreements**
- **Client data isolation** ensures **complete privacy and security**
- **Backup and disaster recovery** provides **business continuity assurance**

### **Security & Privacy:**
- **No unauthorized access** or **penetration testing** beyond owned infrastructure
- **AI and analytics** processing maintains **complete data privacy** with no external exposure
- **VPN and networking services** comply with **local and international regulations**

---

## 🤝 Professional Collaboration

### **Available for:**
- **Infrastructure Consulting** – Enterprise datacenter design and implementation
- **Custom Development** – API development, automation, and integration projects  
- **Security Assessment** – Network architecture review and hardening recommendations
- **Technology Training** – Workshops on self-hosted infrastructure and privacy-focused solutions

### **Contact & Engagement:**
- 💬 **Technical Discussions** – Always interested in infrastructure architecture conversations
- ⭐ **Open Source Contribution** – Star this repository if it provides valuable insights
- 🛠️ **Collaboration Opportunities** – Fork, modify, and build upon these designs
- 📧 **Professional Inquiries** – Available for consulting and development projects

---

**This documentation represents a** ***living infrastructure*** **that continues to evolve with new technologies, client requirements, and professional development goals. Every component serves both personal learning objectives and real-world production requirements — demonstrating the practical application of enterprise technology skills in a comprehensive, scalable environment.**
