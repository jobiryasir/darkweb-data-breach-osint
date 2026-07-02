# 🔍 Hunch.ly: Investigative Evidence Collection

Hunch.ly is a critical tool for OSINT researchers and investigators, specifically designed for verifiable digital evidence collection.

---

## 🕸️ Dark Web Investigation Hub
For deep-dive research into anonymous networks, Hunch.ly maintains a dedicated resource center:
* **[Hunch.ly Dark Web Portal](https://darkweb.hunch.ly/)**: This portal provides specialized content, research, and methodology tailored to the unique complexities of Tor hidden service investigations.

## 🛠️ Advanced Dark Web Methodology
Based on Hunch.ly's research framework, professional investigations should prioritize:

* **Environment Architecture:** Utilizing a "Paranoid" setup (e.g., Whonix Gateway + Buscador VM) to force all system-level traffic through Tor.
* **Evidence Capture:** Always use Hunch.ly to capture ephemeral dark web content, ensuring hashes are generated at the moment of collection to preserve chain of custody.
* **De-anonymization Clues:**
    * **SSL Fingerprinting:** Searching Censys/Shodan for `.onion` certificates misconfigured on surface-web servers.
    * **Historical Verification:** Using [Tor ExoneraTor](https://metrics.torproject.org/exonerator.html) to confirm past Tor network activity for specific IPs.

## 🔗 Key References
* **[Dark Web Setup Guide (PDF)](https://www.hunch.ly/resources/Hunchly-Dark-Web-Setup.pdf)** - Essential technical blueprint.
* **[Hunch.ly Blog](https://hunch.ly/blog/)** - Case studies and advanced OSINT techniques.
* **[Hunch.ly Documentation](https://hunch.ly/docs/)** - Technical configuration guides.

## 💡 Best Practices
* **Chain of Custody:** Always ensure hashing is enabled before beginning your investigation to ensure evidence admissibility.
* **Operational Security:** Separate your "Evidence Collection" environment from your "Anonymous Identity" environment.

---

> **⚠️ Warning:** Always comply with local data protection laws (e.g., GDPR) when collecting and storing third-party data.

[⬅️ Back to Main Directory](readme.md)
