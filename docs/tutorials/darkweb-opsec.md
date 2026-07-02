# 🛡️ Dark Web Operations Security (OpSec) Guide

[![Status](https://img.shields.io/badge/SECURITY-CRITICAL-red?style=flat-square)]()
[![Category](https://img.shields.io/badge/OPSEC-ANONYMITY-brightgreen?style=flat-square)]()

Operations Security (OpSec) is the process of protecting individual identity, behavior, and sensitive data from tracking, surveillance, and correlation while navigating decentralized or darknet ecosystems.

---

## 🚫 Essential OpSec Rules (The Do's and Don'ts)

| 🔴 Never Do (Strictly Prohibited) | 🟢 Always Do (Best Practices) |
| :--- | :--- |
| **Never** use your real name, email, username, or passwords associated with clearnet accounts. | **Always** create completely unique, random pseudonyms and separate credentials for darknet use. |
| **Never** log into personal accounts (Google, Facebook, Bank) while connected to Tor, I2P, or Lokinet. | **Always** use a dedicated, secure browser or a separate privacy-focused operating system. |
| **Never** enable JavaScript or browser plugins/extensions unless absolutely necessary for a verified site. | **Always** keep your browser's security level set to "Safest" or maximize encryption settings. |
| **Never** download files (PDFs, EXEs, DOCX) and open them while online, as they can leak your real IP. | **Always** use secure sandbox environments or open downloaded files completely offline. |

---

## 🌐 Network Routing & Connection Security (Tor vs. VPN)

When structuring your darknet entry path, connection sequence plays a critical role in data isolation and correlation defense.

*   **Tor over VPN (User ➡️ VPN ➡️ Tor):** Hides Tor usage from your local Internet Service Provider (ISP). However, it requires absolute trust in your VPN provider, as they can see your true originating IP address.
*   **VPN over Tor (User ➡️ Tor ➡️ VPN):** Routes VPN traffic through the anonymous network. Highly complex to securely configure and generally discouraged unless preventing exit-node eavesdropping is explicitly required.

### 📖 Verified OpSec Analysis & Documentation
*   **Tor over VPN or Vice Versa:** Comprehensive breakdown of routing configurations, cryptographic handshakes, and operational risks associated with combining anonymity layers.
    *   [🔗 Read Full Analysis on Medium](https://4n6lady.medium.com/tor-over-vpn-or-vice-versa-4a23eb40757d)

---

## 💻 Technical Security Layers

### 1. Browser Hardening & Hygiene
*   **Maximize Windows:** Do not resize your onion/decentralized browser window. Keeping it at default dimensions mitigates **browser fingerprinting** vectors.
*   **Disable WebRTC:** Ensure WebRTC and telemetry parameters are explicitly disabled to eliminate accidental IP leak vulnerabilities.

### 2. Identity Separation (Compartmentalization)
*   **No Metadata:** Strip EXIF and file metadata from any document or image prior to peer-to-peer transmission (utilize utilities like MAT2).
*   **Cryptocurrency OpSec:** Never reuse public wallet addresses. Leverage privacy-centric cryptographic assets and keep darknet operational funds strictly separated from KYC-verified exchanges.

---
[⬅️ Back to Main Directory](README.md)
