# VaultForward.io — Open-Source Offline Decryption Utility

[![License: MIT](https://shields.io)](https://opensource.org)
[![Security: Zero-Knowledge](https://shields.io)](#cryptographic-architecture)
[![Crypto: AES-GCM-256](https://shields.io)](#cryptographic-architecture)

This repository contains the standalone, open-source **Offline Decryption Utility** for [VaultForward.io](https://yggdrasel.com). 

VaultForward is a zero-knowledge digital estate planning and dead man's switch infrastructure. In compliance with strict mathematical data sovereignty, our core principle is that **we never know, store, or transmit your master keys or plaintexts**. 

This completely self-contained HTML/JS file allows designated beneficiaries (recipients) to fully decrypt a released secure payload block locally on an air-gapped machine without ever pinging a remote server.

---

## 🔒 Cryptographic Architecture

The utility utilizes the browser's native Web Crypto API (`crypto.subtle`) for highly optimized, memory-isolated runtime operations. 

Använd koden med försiktighet.[Encrypted Payload Block]+[Owner's Email (Salt)]     --->  [600,000 PBKDF2 Iterations] ---> [Derived AES-GCM Key] ---> [Plaintext Output]+[Beneficiary Access Key]
### Protocol Specifications:
* **Key Derivation (KDF):** PBKDF2 (Password-Based Key Derivation Function 2) running a high-security threshold of **600,000 iterations** using an HMAC-SHA-256 digest wrapper.
* **Cryptographic Salting:** The derivation mechanism binds the cryptographic domain by appending the user’s original structural email directly to the database-generated randomized 32-character hexadecimal salt string (`email + hex_salt`).
* **Symmetric Encryption:** Core content decryption executes via **AES-GCM (Advanced Encryption Standard - Galois/Counter Mode)** featuring an authenticated 256-bit bitlength and unique 12-byte initialization vectors (IVs).

---

## 🚀 How to Run 100% Offline

To ensure complete isolation from remote telemetry, network snooping, or active server dependence, follow these verification steps:

1. **Download the Utility:** Download the standalone `decrypt.html` file from this repository to your machine.
2. **Air-Gap the Environment:** Physically disconnect your computer from the internet (turn off Wi-Fi, unplug Ethernet).
3. **Execute Locally:** Double-click `decrypt.html` to open it in any modern, secure browser (Chrome, Firefox, Brave, Safari).
4. **Input Credentials:**
   * Paste the opaque **Encrypted Payload Block** (received via the triggered beneficiary notification dispatch).
   * Enter the **Vault Owner's Original Email Address** (used as the immutable mathematical salt constraint).
   * Provide your unique offline **Beneficiary Access Key**.
5. **Decrypt:** Click **Execute Client-Side Decryption**. The browser will derive the ephemeral key entirely in volatile RAM, decrypt the buffer, and render the underlying data block locally.

---

## 🕵️‍♂️ Audit the Source

We heavily encourage peer review and technical auditing. The mathematical integrity of the zero-knowledge model means that if a single character of the passphrase, payload block, or email salt is modified or typed incorrectly, the cipher puzzle breaks and outputs a cryptographic failure—proving no backdoor or master recovery mechanism physically exists.

Review the embedded cryptographic script inside `decrypt.html` to inspect:
* Binary stream translation via `TextEncoder()` and `TextDecoder()`.
* Key import structures using `crypto.subtle.importKey`.
* Bitlength constraints and Galois counter integrity metrics during `crypto.subtle.decrypt`.

## 📄 License

This utility is entirely open-source and released under the [MIT License](
