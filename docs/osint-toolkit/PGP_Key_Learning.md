# 🎓 PGP_Key_Learning.md

![LEARNING](https://img.shields.io/badge/CONCEPT-LEARNING-blue?style=flat-square) ![CRYPTOGRAPHY](https://img.shields.io/badge/DOMAIN-CRYPTOGRAPHY-purple?style=flat-square)

This module provides a foundational understanding of PGP (Pretty Good Privacy) mechanics, public-key infrastructure, and the trust models necessary for secure cryptographic communication.

---

### 🧠 Core Concepts

* **Asymmetric Cryptography:** PGP relies on a key pair:
    * **Public Key:** Shared openly to allow others to encrypt messages for you or verify your digital signatures.
    * **Private Key:** Kept strictly confidential and used to decrypt messages or sign documents.
* **The Web of Trust (WoT):** Unlike centralized certificate authorities (CA), PGP uses a decentralized model where users sign each other's keys to establish trust.
* **Fingerprints:** A unique, shorter representation of a public key. It is the primary mechanism for verifying that a key belongs to the intended owner.

---

### 📚 Learning Path & Resources

| Topic | Focus Area | Resource |
| :--- | :--- | :--- |
| **Foundations** | How PGP encryption works | [GnuPG Documentation](https://www.gnupg.org/documentation/index.html) |
| **Trust Models** | Web of Trust vs. TOFU | [PGP Trust Model Explained](https://en.wikipedia.org/wiki/Web_of_trust) |
| **Practical Use** | GPG Command Line Basics | [The GNU Privacy Handbook](https://www.gnupg.org/gph/en/manual.html) |
| **Advanced** | Subkeys and Smartcards | [Debian GPG Best Practices](https://wiki.debian.org/Keysigning) |
| **OSINT Practice** | Extracting data from public keys | [OSINT Dojo (YouTube)](https://www.youtube.com/watch?v=64OrnwmcUOg) |
| **OSINT Research** | Extracting Emails from PGP Sigs | [Medium (Catalyst256)](https://medium.com/@catalyst256/osint-getting-email-addresses-from-pgp-signatures-bf8991e5b624) |
| **OSINT Methodology** | Using PGP keys for OSINT | [LaptrinhX](https://laptrinhx.com/using-pgp-keys-for-osint-1321431286/) |
| **Dark Web Context** | PGP role in privacy and security | [TechNadu](https://www.technadu.com/pgp-encryption-dark-web/57005/) |

---

### ⛓️ Workflow Mechanics

1. **Key Generation:** Creating a master key with optional subkeys for encryption and signing.
2. **Key Distribution:** Publishing the public key to keyservers or personal websites.
3. **Verification:** Confirming the key's authenticity through an out-of-band channel (comparing the fingerprint).
4. **Encryption/Signing:** Using the recipient's public key to encrypt and your private key to sign.
5. **Contextual Awareness:** In dark web environments, PGP is frequently used for identity verification and securing communications to mitigate the risk of interception.

---

### 📝 Self-Assessment Checklist

- [ ] Can I explain the difference between a master key and subkeys?
- [ ] Do I understand the risks associated with keyserver key poisoning?
- [ ] Have I practiced signing and verifying a text file using `gpg`?
- [ ] Do I know how to create a revocation certificate for my own key?
- [ ] Can I extract metadata from a public PGP key using tools like Kleopatra?
- [ ] Do I know how to retrieve email addresses from PGP signatures?

---
[⬅️ Back to Main Directory](readme.md)
