# 🕸️ Dark Web OSINT and OnionScan

![STATUS](https://img.shields.io/badge/TYPE-TECHNICAL-blue?style=flat-square) ![SCOPE](https://img.shields.io/badge/TOPIC-ONION_SCANNING-orange?style=flat-square)

---

### 🔍 Dark Web OSINT Methodology
* **Site Profiling:** Identifying the nature of a hidden service (e.g., forum, marketplace, or informational site) using metadata and content analysis.
* **Attribution Analysis:** Tracking digital footprints such as PGP keys, reuse of CSS/JS files, or unique server headers that correlate across different hidden services.
* **Network Graphing:** Mapping the interconnected nature of dark web entities to identify "tip-of-the-iceberg" versus deep infrastructure.

### 🛠️ OnionScan & Automated Analysis
* **OnionScan Functionality:** A specialized tool designed to crawl and analyze .onion sites to detect security vulnerabilities, misconfigurations, and potential leaks.
* **Vulnerability Assessment:** Automates the discovery of exposed internal IP addresses, hidden server configurations, and sensitive information accidentally published on the web server.
* **Data Extraction:** Extracts metadata, titles, and headers from crawled pages to populate intelligence databases for further analysis.

### 📊 Reports & Foundational Case Studies
* **[Vice: A Tool to Check If Your Dark Web Site Really Is Anonymous](https://www.vice.com/en/article/kb7bg3/onionscan-checks-if-your-dark-web-site-really-is-anonymous/)** – Background on how the tool detects de-anonymization vectors.
* **[Mascherari Press: OnionScan Report (June 2016)](https://mascherari.press/onionscan-report-june-2016/)** – Early findings on widespread security flaws in hidden services.
* **[Mascherari Press: Forensic Finances and Dark Markets](https://mascherari.press/onionscan-report-forensic-finances-dark-markets/)** – Intersection of financial tracking and dark web market investigations.
* **[Mascherari Press: FHII, A New Map and the Future](https://mascherari.press/onionscan-report-fhii-a-new-map-and-the-future/)** – Incident analysis of the Freedom Hosting II compromise.

### 🎥 Expert Presentations & Tutorials
* **[Sarah Jamie Lewis - OnionScan: Practical Deanonymization of Hidden Services](https://www.youtube.com/watch?v=r8hr0nlfJRc)** – The creator explains the philosophy and technical flaws behind Tor hidden services.
* **[CYBR 4360 - OnionScan and Shodan - Automating OSINT](https://www.youtube.com/watch?v=ydcid_e5gtU)** – Practical guide on combining OnionScan with Shodan to automate infrastructure mapping.

### 🔗 Essential Tools & Resources
* **[OnionScan GitHub Repository](https://github.com/s-rah/onionscan)** – Primary source code and documentation.
* **[OnionScan Official Site](https://onionscan.org/)** – Project homepage.
* **[Tor ExoneraTor](https://exonerator.torproject.org/)** – Tool to verify if an IP was a Tor relay on a specific date.

### ⚠️ Technical Safety Protocols
* **Isolation:** Onion scanning should never be performed from a production environment; always use hardened, non-persistent virtual machines.
* **Proxy Chaining:** Ensure all scan traffic is routed through the Tor network.
* **Metadata Sanitization:** Scrub all files downloaded during scanning of EXIF, GPS, or other identifying metadata before offline analysis.

> **IMPORTANT:** Automated scanning is noisy and can be detected by site administrators. Review target policies and legal boundaries before deep-scan operations.

[⬅️ Back to Main Directory](readme.md)
