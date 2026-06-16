<div align="center">
  <h1>🛡️ Vendly Marketplace Script</h1>
  <p><b>The Ultimate Privacy-First, Zero-Trace E-Commerce Solution</b></p>
</div>

<br>

## ⚙️ Core Architecture & Codebase
Vendly is written in **Ruby on Rails** and runs completely self-hosted. The backend uses a standard **PostgreSQL** database to manage market data, **Redis** for quick caching, and **Sidekiq** background workers to handle the on-chain Monero payment tracking. The entire environment is fully containerized with **Docker** (`docker-compose`), meaning you can spin up the whole system on any Linux VPS with one command.

---

## 🌐 Live Demo
* **Tor Onion Address:** `http://j4wxdmsxeoyog5bewm2whrqjcrbszg3uhtv22im4yo7cv43ay5gzhjyd.onion`
* **Admin Demo:** `Username: admindemo` | `Password: Admin123` *(Login via `/_pnl_3f9a2b8e`)*
* **Vendor Demo:** `Username: testvendor` | `Password: Vendor123`

---

## 💎 Features

### 🔒 Privacy & Cyber Security
* JavaScript-Free Frontend (Tor Browser native compatibility)
* Zero-Trace Policy (Instant IP & session purge from server logs)
* Custom "Broken Circle" Visual/Mathematical Captcha (Anti-DDoS)
* Mandatory PGP Encryption for delivery addresses
* Integrated PGP-encrypted internal messaging system
* PGP-based Two-Factor Authentication (2FA) for vendors and buyers

### 🪙 Blockchain & Payment Processing
* 100% Self-Hosted Monero RPC Node integration (Zero 3rd-party APIs)
* Dynamic unique XMR address generation per order
* Configurable order expiration countdown (e.g., 12 hours)
* Automated blockchain scanning for exact amounts & block confirmations
* Automated handler for underpayment and overpayment edge cases

### 🛒 Commerce & Operations
* One-product-per-order checkout flow (Batch payment supported)
* Native support for Physical, Digital, and Dead Drop products
* Multi-tier options: Custom pricing, shipping locations, and 3 images per product
* Instant product cloning template system
* Stealth product hiding and instant sales toggle
* Multi-currency support with real-time fiat exchange rates
* Order archiving for clean vendor dashboards

### 🏛️ Escrow, Commissions & Administration
* Strict privileges separation between Site Admin and Marketplace Vendors
* Multi-party Escrow & Dispute resolution system
* "Finalize Early" (FE) / No-Escrow privileges toggle for trusted vendors
* Automated background payouts to vendor cold wallets upon order finalization
* Stealth Admin Portal for managing users, disputes, tickets, and global news
* Built-in multi-tier Dynamic Affiliate referral system
* Fully Dockerized infrastructure (`docker-compose`)

---

## ⚖️ Legal Disclaimer & Terms of Use
**Read carefully before contacting.**

* **Developer Status:** The creator of this codebase is an independent software developer. The developer is **not** engaged in, affiliated with, or responsible for any operations, sales, or activities conducted by individuals who purchase and deploy this source code.
* **Educational & Legal Use Only:** "Vendly" is a software script intended solely for educational research, penetration testing, and the creation of legal, privacy-centric e-commerce platforms. 
* **No Liability:** By purchasing or downloading this source code, you agree that you are solely responsible for how the script is utilized. The developer assumes zero liability for any illicit, illegal, or prohibited activities facilitated by the deployment of this codebase. 
* **No Technical Support for Illicit Use:** Technical support will be immediately terminated if the developer becomes aware the source code is being utilized to violate local, federal, or international laws.
---

## 📦 Licensing & Setup Inquiries

> ⚠️ **NOTICE:** This repository serves as the official documentation hub. The full source code is strictly licensed and not publicly distributed here.

Vendly is exclusively available via private **Script Licensing**. 

**Included with a License:**
1. Full, unencrypted source code (Ruby on Rails + Docker configurations).
2. Comprehensive deployment documentation (`INSTALL.md` and `SETUP.txt`).
3. 30 Days of direct technical guidance for server architecture and setup via Telegram.

### 📩 Let's Talk:
We are open to negotiation. Message **[@vendlydev](https://t.me/vendlydev)** on Telegram to discuss pricing options, view the live `.onion` demo, and secure your license.
