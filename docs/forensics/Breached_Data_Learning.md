# 📚 Breached Data Learning & Analysis

![EDUCATION](https://img.shields.io/badge/LEARNING-BREACH_ANALYSIS-blue?style=flat-square) ![SECURITY](https://img.shields.io/badge/SECURITY-FUNDAMENTALS-green?style=flat-square)

### 🧠 Core Concepts
* **What is Breach Data?** Data made publicly available by entities that perpetrate unauthorized breaches. 
* **Operational Risk:** Always check organizational policy before using breach data, as it is stolen and legally sensitive information.
* **Credential Stuffing:** Using leaked email/password pairs to gain access to other platforms.
* **Hash Correlation:** Using password hashes to link multiple accounts together without needing the plaintext password.

### 🛡️ OPSEC & Anonymity (Exposing the Invisible Guide)
* **Tails (The Amnesic Incognito Live System):** The safest OS for investigating leaks; runs from USB, routes all traffic through Tor, and leaves no trace on the host machine.
* **Tor Browser:** Protects anonymity by routing traffic through three random volunteer nodes.
* **Onion Services:** Use these for accessing platforms (like SecureDrop) that hide their physical location and ensure encrypted, anonymous communication.
* **Risk Protocol:** Treat all leaked data as "hostile." Never open on your main system. Use a sandboxed environment or non-persistent VM.

### 📺 Key Techniques & OSINT Tradecraft
* **Email Pivot:** Searching breached databases using a target's email to uncover leaked credentials.
* **Password Patterns:** Identifying keyboard patterns or reused passwords to map account activity.
* **Cultural Context:** Searching for passwords in different character sets (e.g., Cyrillic/Russian) to find relevant leaks.
* **POS Malware Analysis:** Understanding how malware scans memory for credit card track data.
* **Darknet Monitoring:** Detecting leaked credentials early using secure mining services.

### 🔗 Research References
1. [Exposing the Invisible: Leak and Onion Soup](https://exposingtheinvisible.org/en/guides/leak-and-onion-soup/)
2. [LISA18 - Anatomy of a Crime (YouTube)](https://www.youtube.com/watch?v=hre764FUCKA)
3. [OSINT Curious: Basics of Breach Data](https://osintcurio.us/2019/05/21/basics-of-breach-data/)
4. [10 Minute Tip: Searching Breach Data for OSINT (YouTube)](https://www.youtube.com/watch?v=UeI7wEdLPn8)
5. [Tor Project: Official Documentation](https://support.torproject.org/)
6. [Damn Vulnerable Web App (DVWA)](https://github.com/digininja/DVWA)

### 🛡️ RESEARCHER SAFETY WARNING
> **CRITICAL WARNING:** Direct interaction with underground sites like Doxbin or unverified paste sites is **extremely harmful**. These platforms are primary distribution vectors for malware and phishing.
> 
> **PROTOCOL:** 
> 1. Never visit these sites on your host machine.
> 2. Always use an isolated, non-persistent VM or Tails.
> 3. Use secure aggregators (e.g., Intelligence X) rather than direct navigation.
> 4. Keep your OPSEC strict: assume all leaks are compromised or bait.

[⬅️ Back to Main Directory](readme.md)
