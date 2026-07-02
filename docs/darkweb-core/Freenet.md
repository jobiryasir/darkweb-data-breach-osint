# 🦋 Hyphanet (Formerly Freenet) Peer-to-Peer Resources & Deployment

[![Status](https://img.shields.io/badge/HYPHANET-ACTIVE-teal?style=flat-square)]()
[![Category](https://img.shields.io/badge/OSINT-DATA_STORE-blue?style=flat-square)]()

This file contains a curated collection of official installation parameters, technical documentation, and infrastructure guidelines for understanding and investigating the decentralized Hyphanet (formerly Freenet) peer-to-peer network ecosystem securely.

---

## 📌 Verified Hyphanet Resources

| Platform / Service Name | Purpose & Investigation Use Case | Direct Access |
| :--- | :--- | :---: |
| **Hyphanet Official Website** | Primary gateway for downloading the core platform, tracking development blogs, and official project updates. | [🌐 Visit Site](https://www.hyphanet.org/index.html) |
| **Hyphanet GitHub Core** | Repository containing the core implementation, node connection logic, and decentralized routing system. | [🐙 View Repository](https://github.com/freenet/fred) |
| **Freenet Anonymity Overview Guide** | Third-party threat intelligence analysis regarding Freenet/Hyphanet node security and data-store anonymity mechanics. | [📰 Read Article](https://www.darkweblist.com/2019/anonymity/freenet-another-secure-anonymity-browser/) |
| **Empirical Study of Cryptomining (ACM)** | Academic research paper analyzing malicious footprints and the propagation of hidden cryptomining code within the Freenet data-store framework. | [🔬 View Paper](https://dl.acm.org/doi/10.1145/3372297.3417876) |
| **Freenet/Freenu Place Practical Guide** | Video demonstration and practical walk-through explaining deployment mechanics and privacy configurations. | [📺 Watch Video](https://www.youtube.com/watch?v=zu9gM3_gIfM) |

---

## ⚙️ Core Installation Parameters (Headless Server Deployment)

To host a headless Hyphanet node on an external Linux server (VPS) and run its setup daemon securely, use the following operational framework:

### 1. Download & Execute the Headless Installer
```bash
wget '[https://github.com/freenet/fred/releases/download/build01506/freenet-headless-installer.jar](https://github.com/freenet/fred/releases/download/build01506/freenet-headless-installer.jar)' -O freenet-installer.jar
java -jar freenet-installer.jar -console
