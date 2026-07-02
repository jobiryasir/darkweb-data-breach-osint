# 🌐 Invisible Internet Project (I2P) Resources & Deployment

[![Status](https://img.shields.io/badge/I2P_NETWORK-ACTIVE-purple?style=flat-square)]()
[![Category](https://img.shields.io/badge/OSINT-DARKNET_INFRASTRUCTURE-blue?style=flat-square)]()

This file contains a curated collection of official gateways, technical documentation, installation guides, and essential entry points for understanding, deploying, and investigating the peer-to-peer decentralized I2P network ecosystem securely.

---

## 📌 Verified I2P Resources

| Platform / Service Name | Purpose & Investigation Use Case | Direct Access |
| :--- | :--- | :---: |
| **I2P Project Official (Global Mirror)** | Primary web gateway for the Invisible Internet Project containing distribution binaries, installation guides, and protocol specifications. | [🌐 Visit Site](https://i2p.net/en/) |
| **I2P Network Hub (GetI2P)** | Direct development ecosystem mirror for tracking codebase releases, developer logs, and core network database adjustments. | [🌐 Visit Site](https://geti2p.net/) |
| **Introduction to I2P (Aaron Jones)** | An advanced security lecture detailing unidirectional tunneling, garlic routing mechanics ("cloves"), internal Web 2.0 vulnerabilities (JavaScript/PHP/MySQL), browser exploits, and low-level hardware persistence. | [📺 Watch Video](https://www.youtube.com/watch?v=o3CSTP86VHM) |
| **I2P Deployment Presentation** | Complete technical breakdown of headless I2P orchestration, headless installation variables, remote router panel binding via SSH port forwarding, and local proxy alignment configurations. | [🌐 View Presentation](https://retro64xyz.gitlab.io/presentations/2018/03/13/introduction-to-i2p/#how-to-install) |

---

## ⚙️ Core Installation Parameters (Remote VPS Deployment)
To host an isolated I2P router externally on a headless machine and manage it via secure local configurations, use the following operational framework:

### 1. Download & Launch Binary
```bash
wget '[https://download.i2p2.de/releases/0.9.33/i2pinstall_0.9.33.jar](https://download.i2p2.de/releases/0.9.33/i2pinstall_0.9.33.jar)' -O new_installer_offline.jar
java -jar new_installer_offline.jar
