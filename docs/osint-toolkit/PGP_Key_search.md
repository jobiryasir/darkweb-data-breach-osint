# 🔑 PGP Key search

![PGP](https://img.shields.io/badge/CRYPTOGRAPHY-PGP-orange?style=flat-square) ![SECURITY](https://img.shields.io/badge/SECURITY-ENCRYPTION-red?style=flat-square)

This documentation serves as a centralized directory for platforms used to locate, verify, and manage public PGP keys, essential for secure communication and identity verification in investigative research.

---

### 📌 Indexed PGP Key Resources

| Platform / Source | Utility | Access |
| :--- | :--- | :--- |
| **OpenPGP Key Servers** | Global directory for public key discovery | [Click Here](https://keys.openpgp.org/) |
| **PeeGeePee** | Searchable PGP key directory | [Click Here](https://peegeepee.com/) |
| **MIT PGP Public Key Server** | Historical public key database | [Click Here](https://pgp.mit.edu/) |
| **GnuPG Key Server** | Distributed GPG keyserver network | [Click Here](http://keys.gnupg.net/) |
| **Symantec/Broadcom PGP Keyserver** | Enterprise key discovery | [Click Here](https://keyserver.pgp.com/vkd/GetWelcomeScreen.event) |
| **Keybase** | Identity linking & verification | [Click Here](https://keybase.io/) |
| **Proton Mail Key Search** | Verifying Proton contacts | [Click Here](https://proton.me/) |

---

### 🛡️ PGP Security & Verification Guidelines

* **Verify Fingerprints:** Never rely solely on a key server match. Always verify the PGP fingerprint through an out-of-band channel (e.g., official website, encrypted chat, or signed message) before importing.
* **Avoid Key Poisoning:** Be cautious of "key poisoning" attacks where malicious keys are uploaded to public servers with fake UIDs.
* **Use Local Keyrings:** Manage your keys in a local, encrypted keyring (e.g., GnuPG/GPG). Exported public keys should be stored in your offline, encrypted research container.
* **Key Expiration & Revocation:** Regularly audit your keyring for expired keys and check for revocation certificates for any critical contacts.

---

### 🔍 Verification Checklist

- [ ] **Identity Confirmation:** Have you verified the fingerprint via a trusted secondary source?
- [ ] **GPG Import:** Have you imported the key into your local GPG keyring using `gpg --import keyfile.asc`?
- [ ] **Trust Assignment:** Have you assigned an appropriate trust level (e.g., `gpg --edit-key`) to verified keys?
- [ ] **Signature Verification:** Always check the digital signature of sensitive documents before trust evaluation.

---
[⬅️ Back to Main Directory](readme.md)
