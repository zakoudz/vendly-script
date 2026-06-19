<div align="center">
  <h1>🛡️ Vendly Marketplace Script</h1>
  <p><b>The Ultimate Tor-Native, Privacy-First, Zero-Trace E-Commerce Engine</b></p>
  
  <code>Tor Onion Core</code> • <code>Ruby on Rails</code> • <code>PostgreSQL</code> • <code>Redis</code> • <code>Docker</code> • <code>Monero RPC</code>
</div>

---

## ⚡ Overview
**Vendly** is a fully containerized, production-ready e-commerce platform engineered specifically for **Tor Hidden Services (.onion)**. Built on **Ruby on Rails** and optimized for darknet routing resilience, it eliminates third-party dependencies, trackers, and clear-text logs entirely to guarantee absolute anonymity.

### 🌐 Live Environments
* **Tor Onion Service:** `http://j4wxdmsxeoyog5bewm2whrqjcrbszg3uhtv22im4yo7cv43ay5gzhjyd.onion`
* **Admin Panel:** `/_pnl_3f9a2b8e` *(User: `admindemo` | Pass: `Admin123`)*
* **Vendor Demo:** *(User: `testvendor` | Pass: `Vendor123`)*

---

<div align="center" style="background: linear-gradient(145deg, #111, #1a1a1a); border: 1px solid #0088cc; padding: 30px; border-radius: 12px; margin: 30px 0; box-shadow: 0 8px 24px rgba(0,136,204,0.1);">
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/telegram.svg" width="60" height="60" style="margin-bottom: 15px; filter: invert(41%) sepia(93%) saturate(1239%) hue-rotate(178deg) brightness(97%) contrast(103%);" alt="Telegram">
  <h2 style="margin-top: 0; color: #fff; font-weight: 700; letter-spacing: 0.5px;">⚡ Join the Vendly HQ Community</h2>
  <p style="color: #ccc; font-size: 15px; max-width: 550px; margin: 10px auto 25px auto; line-height: 1.6;">
    Connect with privacy-focused core developers, track real-time script changelogs, receive critical security updates, and discuss custom deployment architectures.
  </p>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px;">
    <a href="https://t.me/vendlyscript" target="_blank" style="background: #0088cc; color: #fff; padding: 14px 28px; text-decoration: none; font-weight: bold; border-radius: 6px; font-size: 14px; transition: background 0.2s ease; box-shadow: 0 4px 12px rgba(0,136,204,0.3);">💬 Enter Dev Community</a>
    <a href="https://t.me/vendlydevs" target="_blank" style="background: transparent; color: #0088cc; padding: 12px 26px; text-decoration: none; font-weight: bold; border-radius: 6px; font-size: 14px; border: 2px solid #0088cc; transition: all 0.2s ease;">📬 Direct OTC Inquiries</a>
  </div>
</div>

---

## ⚙️ Core Architecture & Tor Optimization
Designed for rapid deployment and seamless scaling via onion routing on any hardened Linux VPS.

* **Tor-Optimized Frontend:** No Javascript dependency, ensuring full compatibility with Tor Browser's "Safest" security level.
* **Backend Engine:** Ruby on Rails (Clean, modular MVC architecture).
* **Data & Caching:** PostgreSQL (Relational data) + Redis (Session & cache management).
* **Asynchronous Tasks:** Sidekiq background workers for blockchain monitoring.
* **Deployment:** Pre-configured `docker-compose` environment integrating Tor daemon configurations out-of-the-box.

---

## 💎 Key Features

### 🔒 Tor-Native Security & Privacy
* **JS-Free Frontend:** Zero client-side scripts to protect users against browser-exploit deanonymization.
* **Zero-Log Infrastructure:** Automatic, instant purging of remote IP addresses and session logs at the web-server level.
* **Layer 7 DDoS Protection:** Built-in Tor-friendly "Broken Circle" visual/mathematical captcha designed to mitigate malicious onion circuit flooding.
* **Cryptographic Layer:** Mandatory PGP encryption for communications, delivery data, and 2FA authentication.

### 🪙 Native Blockchain Integration
* **Self-Hosted Monero (XMR) Node:** Independent payment validation operating entirely behind Tor proxies without external APIs.
* **Pool-Based Address Distribution:** Eliminates real-time wallet creation flaws. Admin pre-generates Monero sub-addresses manually or via an automated auth-script. Addresses are stored in PostgreSQL, bound on-demand to current checkouts, and permanently wiped post-transaction to maintain zero audit trails.
* **Edge-Case Resolution:** Background workers handle underpayments, overpayments, and block confirmations autonomously.

### 🏛️ Marketplace Operations
* **Multi-Tier Escrow:** Advanced system handling traditional escrow, multi-party dispute resolution, and Finalize Early (FE) permissions.
* **Automated Payouts:** Instant background transfers directly to vendor cold wallets upon order completion.
* **Product Management:** Supports physical, digital, and dead drop listings with dynamic pricing and internal cloning.

---

## 📸 Interface Preview
<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; align-items: center; max-width: 1200px; margin: 20px auto;">
  <img src="https://github.com/user-attachments/assets/22ff3f79-4202-4534-97f8-5d1675cfaec5" width="32%" style="border-radius: 6px; border: 1px solid #333;" alt="Dashboard">
  <img src="https://github.com/user-attachments/assets/3f7bb082-de60-4023-9e83-39eb203294d1" width="32%" style="border-radius: 6px; border: 1px solid #333;" alt="Listings">
  <img src="https://github.com/user-attachments/assets/a134b56f-d371-4e3a-8b44-9e603aea71b4" width="32%" style="border-radius: 6px; border: 1px solid #333;" alt="Disputes">
</div>

---

## 📦 Licensing & Technical Support
This repository contains documentation and architectural overview. The core codebase is proprietary and distributed via private licensing agreements.

### What’s Included:
1. Complete unencrypted source code with full Git history.
2. Production-ready Docker deployment files with integrated Tor configurations (`INSTALL.md`, `SETUP.txt`).
3. 30 days of direct server architecture, Tor routing, and deployment support.

---

## ⚖️ Legal Disclaimer & Limitation of Liability

**IMPORTANT NOTICE: PLEASE READ CAREFULLY BEFORE USE, DOWNLOAD, OR INTERACTION.**

1. **Academic & Research Purpose Only:** This codebase is provided strictly as a reference implementation for educational research, cryptographic studies, and private security audits within the Tor network ecosystem. It is not intended, designed, or licensed for deployment in jurisdictions where privacy-focused commerce platforms or unhosted cryptographic escrow systems are restricted or illegal.

2. **No Operational Affiliation:** The developer is purely an independent software author. The developer does not operate, host, moderate, or maintain any active deployment or `.onion` hidden service of this script, nor does the developer have any technical access, control, or visibility into setups managed by third parties. 

3. **As-Is Provision & No Warranty:** The software is provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the author or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

4. **Zero Liability for Third-Party Misuse:** The user assumes absolute and sole legal responsibility for compliance with all local, federal, and international laws. The developer explicitly disclaims any and all liability for illicit activities, financial losses, regulatory non-compliance, or malicious modifications conducted by downstream users or licensors.
