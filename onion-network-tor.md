# 🧅 Onion Network (Tor) Resources

[![Status](https://img.shields.io/badge/ONION_NETWORK-ACTIVE-brightgreen?style=flat-square)]()
[![Category](https://img.shields.io/badge/OSINT-INFRASTRUCTURE-blue?style=flat-square)]()

This file contains a curated collection of official gateways, infrastructure guides, technical video lectures, and essential entry points for investigating the Tor ecosystem securely.

---

## 📌 Verified Onion & Tor Resources

| Platform / Service Name | Purpose & Investigation Use Case | Direct Access |
| :--- | :--- | :---: |
| **Tor Project** | The official platform for downloading the Tor Browser and accessing core anonymity network documentation. | [🌐 Visit Site](https://www.torproject.org/) |
| **How TOR Works (Computerphile)** | A deep-dive video lecture explaining Onion Routing, multi-layered encryption, circuit building, and basic network hops. | [📺 Watch Video](https://www.youtube.com/watch?v=QRYzre4bf7I) |
| **Why & How to Use Onion Networking** | Expert presentation detailing end-to-end decentralized networks, self-authenticating .onion addresses, cryptographic guarantees, and dynamic introduction points. | [📺 Watch Video](https://www.youtube.com/watch?v=pebRZyg_bh8) |
| **Tor Hidden Services (Computerphile)** | Breakdown of how Tor Onion Services register introduction points, publish signed descriptors to the DHT directory, and safely meet clients at a Rendezvous Point. | [📺 Watch Video](https://www.youtube.com/watch?v=lVcbq_a5N9I) |
| **Tor Traffic Analysis (Computerphile)** | An advanced security lecture focused on metadata leaks, timing correlation attacks, guard node tracking, and the mathematical limitations of absolute anonymity against global network passive observers. | [📺 Watch Video](https://www.youtube.com/watch?v=BSQCI4fqW88) |

---

## 💡 Quick Investigation Tips for Tor
* Always route through a clean, isolated environment before interacting with underground services.
* Verify the cryptographic hashes or signatures of onion directories when performing deep OSINT research.
* **Traffic Analysis Shield:** Be aware that while payloads are fully encrypted, a passive global adversary can monitor the *timing* and *volume* of traffic entering and exiting nodes to correlate identities. Always rotate circuits and use trusted Guard Nodes.

---
[⬅️ Back to Main Directory](README.md)
