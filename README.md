<div align="center">
  <h1>🛡️ Vendly Marketplace Script</h1>
  <p><b>The Ultimate Privacy-First, Zero-Trace E-Commerce Engine</b></p>
  
  <code>Ruby on Rails</code> • <code>PostgreSQL</code> • <code>Redis</code> • <code>Docker</code> • <code>Monero Core</code>
</div>

---

## ⚡ Overview
**Vendly** is a fully containerized, production-ready e-commerce platform engineered for absolute privacy and resilience. Built on **Ruby on Rails** and powered by a self-hosted architecture, it eliminates third-party dependencies, trackers, and logs entirely.

### 🌐 Live Environments
* **Tor Onion Service:** `http://j4wxdmsxeoyog5bewm2whrqjcrbszg3uhtv22im4yo7cv43ay5gzhjyd.onion`
* **Admin Panel:** `/_pnl_3f9a2b8e` *(User: `admindemo` | Pass: `Admin123`)*
* **Vendor Demo:** *(User: `testvendor` | Pass: `Vendor123`)*

---

## 🛠️ Core Architecture
Designed for rapid deployment and seamless scaling on any Linux VPS.

* **Backend Engine:** Ruby on Rails (Clean, modular MVC architecture).
* **Data & Caching:** PostgreSQL (Relational data) + Redis (Session & cache management).
* **Asynchronous Tasks:** Sidekiq background workers for blockchain monitoring.
* **Deployment:** Pre-configured `docker-compose` environment for single-command setup.

---

## 💎 Key Features

### 🔒 Hardened Security & Privacy
* **JS-Free Frontend:** Seamless, native compatibility with Tor Browser high-security settings.
* **Zero-Log Infrastructure:** Automatic, instant purging of IP addresses and session logs.
* **Advanced Protection:** Built-in "Broken Circle" visual/mathematical captcha to mitigate Layer 7 DDoS attacks.
* **Cryptographic Layer:** Mandatory PGP encryption for communications, delivery data, and 2FA authentication.

### 🪙 Native Blockchain Integration
* **Self-Hosted Monero (XMR) Node:** Independent payment validation without external payment gateways or APIs.
* **Dynamic Checkout:** Automated generation of unique sub-addresses per order with real-time expiration countdowns.
* **Edge-Case Resolution:** Background workers handle underpayments, overpayments, and block confirmations autonomously.

### 🏛️ Marketplace Operations
* **Multi-Tier Escrow:** Advanced system handling traditional escrow, multi-party dispute resolution, and Finalize Early (FE) permissions.
* **Automated Payouts:** Instant background transfers directly to vendor cold wallets upon order completion.
* **Product Management:** Supports physical, digital, and dead drop listings with dynamic pricing and internal cloning.

---

## 📸 Interface Preview
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 10px; margin: 20px 0;">
  <img src="https://github.com/user-attachments/assets/22ff3f79-4202-4534-97f8-5d1675cfaec5" alt="Dashboard" style="border-radius:6px; border:1px solid #333;">
  <img src="https://github.com/user-attachments/assets/3f7bb082-de60-4023-9e83-39eb203294d1" alt="Listings" style="border-radius:6px; border:1px solid #333;">
  <img src="https://github.com/user-attachments/assets/a134b56f-d371-4e3a-8b44-9e603aea71b4" alt="Disputes" style="border-radius:6px; border:1px solid #333;">
</div>

---

## 📦 Licensing & Technical Support
This repository contains documentation and architectural overview. The core codebase is proprietary and distributed via private licensing agreements.

### What’s Included:
1. Complete unencrypted source code with full Git history.
2. Production-ready Docker deployment files (`INSTALL.md`, `SETUP.txt`).
3. 30 days of direct server architecture and deployment support.

### 📩 Secure Your License
Connect with our development team directly to verify the live demo, discuss pricing, or inspect the codebase structure:

* **Telegram Contact:** [@vendlydevs](https://t.me/vendlydevs)
* **Community Updates:** [@vendlyscript](https://t.me/vendlyscript)

---

<small><b>Disclaimer:</b> This software is intended exclusively for educational research, security audits, and authorized deployment scenarios. The developer accepts zero liability for modifications or operational misuse by third parties.</small>
