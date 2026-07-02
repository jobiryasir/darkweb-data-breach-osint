# 🛡️ OSINT & Infrastructure Analysis: Master Toolkit

This guide consolidates dark web investigation, favicon fingerprinting, and origin IP discovery techniques into a single reference.

---

## 📑 Section 1: Dark Web OSINT and OnionScan
### 🛠️ OnionScan & Automated Analysis
* **[OnionScan GitHub](https://github.com/s-rah/onionscan)** - Primary source code and documentation.
* **[Vice: OnionScan Review](https://www.vice.com/en/article/kb7bg3/onionscan-checks-if-your-dark-web-site-really-is-anonymous/)** - Overview of functionality and purpose.

### 📊 Reports & Case Studies
* **[Mascherari Press (June 2016)](https://mascherari.press/onionscan-report-june-2016/)** - Analysis of security flaws and vulnerabilities.
* **[Forensic Finances](https://mascherari.press/onionscan-report-forensic-finances-dark-markets/)** - Financial transaction patterns in dark markets.
* **[FHII Compromise](https://mascherari.press/onionscan-report-fhii-a-new-map-and-the-future/)** - Freedom Hosting II breach survey.

### 🎥 Expert Talks
* **[Sarah Jamie Lewis Talk](https://www.youtube.com/watch?v=r8hr0nlfJRc)** - Practical de-anonymization of hidden services.
* **[OnionScan & Shodan Automation](https://www.youtube.com/watch?v=ydcid_e5gtU)** - Automated OSINT pipeline development.

---

## 📑 Section 2: Favicon Investigation Techniques
### 🔍 Core Concept
Leveraging favicon hashes to link infrastructure or identify shared backend servers.

### 🔧 Recommended Tooling
* **[FavFreak (GitHub)](https://github.com/devanshbatham/FavFreak)** - Tool for automated reconnaissance.
* **[Fav-Up (GitHub)](https://github.com/pielco11/fav-up)** - Favicon hash generator.

### 🎥 Tutorials & Guides
* **[Weaponizing Favicons (Medium)](https://medium.com/@Asm0d3us/weaponizing-favicon-ico-for-bugbounties-osint-and-what-not-ace3c214e139)** - Advanced reconnaissance pipeline.
* **[Shodan via Favicon Hash (Video)](https://www.youtube.com/watch?v=K2BXHS0Qm0o)** - Practical walkthrough.

---

## 📑 Section 3: De-anonymization & Origin IP Discovery
### 🕵️ Core Objective
Revealing the true origin IP address of servers hidden behind CDNs (like Cloudflare) or Tor.

### 🛠️ Common Techniques
* **Historical DNS:** Analyzing records via SecurityTrails or ViewDNS for pre-protection IP exposure.
* **SSL Fingerprinting:** Querying Shodan/Censys using certificate hashes to locate origin servers.
* **Favicon Tracing:** Identifying infrastructure through unique favicon hash matches.

### 🔗 Essential Resources
* **[SECJuice Guide](https://www.secjuice.com/finding-real-ips-of-origin-servers-behind-cloudflare-or-tor/)** - Comprehensive guide on origin IP discovery.
* **[Censys](https://search.censys.io/) / [Shodan](https://shodan.io/)** - Global infrastructure search engines.

---

> **⚠️ Ethical Warning:** Ensure all investigative activities remain within legal boundaries and authorized scopes. Automated scanning can be intrusive and detectable.
