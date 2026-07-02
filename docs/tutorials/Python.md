# 🐍 Python

![PYTHON](https://img.shields.io/badge/PYTHON-SCRIPTS-green?style=flat-square) ![AUTOMATION](https://img.shields.io/badge/AUTOMATION-ACTIVE-blue?style=flat-square)

This repository contains custom Python scripts designed for data parsing, automated security auditing, and handling intelligence feeds related to dark web investigations.

---

### 📌 Indexed Scripts & Utilities

| Script Name | Functionality | Status |
| :--- | :--- | :--- |
| `onion_crawler.py` | Scrapes metadata from specified onion domains | Experimental |
| `pdf_scrubber.py` | Removes EXIF and document metadata from PDFs | Active |
| `intel_parser.py` | Standardizes JSON-based cyber threat intelligence | Stable |
| `proxy_rotator.py` | Manages rotation for outbound investigative traffic | Stable |

---

### 📚 Research & Methodology References

| Resource | Focus Area | Access |
| :--- | :--- | :--- |
| Towards Data Science | Locating Dark Web Hacker Forums | [Click Here](https://towardsdatascience.com/how-to-locate-dark-web-hacker-forums-for-security-research-e87b53f18508) |
| Towards Data Science | Techniques to Scrape the Dark Web | [Click Here](https://towardsdatascience.com/how-to-scrape-the-dark-web-53145add7033) |
| BSidesMCR 2019 (YouTube) | OSINT & Python for Tor/Darkweb | [Click Here](https://www.youtube.com/watch?v=wo4InxoM09Q) |
| Python Italia (YouTube) | Darkweb + Python: Discover, Analyze, Extract | [Click Here](https://www.youtube.com/watch?v=pJEPUHZntfA) |

---

### ⛓️ Execution Guidelines

* **Sandboxing:** Run all scripts within a dedicated virtual environment (`venv`) or container (Docker) to ensure library isolation and security.
* **Network Isolation:** Ensure scripts configured for network activity are routed exclusively through your configured proxy or Tor daemon.
* **Code Auditing:** Review all scripts before execution, especially those involving automated network requests or filesystem operations.

---

### 🔍 Development Checklist

- [ ] **Dependencies:** Ensure all required libraries (e.g., `requests`, `beautifulsoup4`, `PyPDF2`, `stem`) are installed in the `requirements.txt` file.
- [ ] **Environment Variables:** Never hardcode API keys or credentials; use a local `.env` file excluded from version control.
- [ ] **Logging:** Implement robust logging to track script execution and error handling during long-running tasks.
- [ ] **Cleanup:** Ensure temporary files created by scripts are securely wiped after task completion.

---
[⬅️ Back to Main Directory](readme.md)
