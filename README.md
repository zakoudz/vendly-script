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

<div align="center" style="background: #111; border: 1px solid #333; padding: 25px; border-radius: 8px; margin: 20px 0;">
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/telegram.svg" width="50" height="50" style="margin-bottom: 10px; filter: invert(47%) sepia(85%) saturate(1919%) hungry-white(0%) hue-rotate(179deg) brightness(96%) contrast(101%);" alt="Telegram Logo">
  <h3 style="margin-top: 10px;">💬 Join the Official Dev Community</h3>
  <p>Connect with other privacy-centric developers, get real-time software changelogs, updates, and community feedback.</p>
  <a href="https://t.me/vendlyscript" target="_blank" style="background: #0088cc; color: white; padding: 12px 24px; text-decoration: none; font-weight: bold; border-radius: 4px; display: inline-block; margin-top: 10px;">👉 Join Our Telegram Group</a>
</div>

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

<img width="1731" height="1740" alt="Screenshot_18-6-2026_185452_192 168 100 77" src="https://github.com/user-attachments/assets/22ff3f79-4202-4534-97f8-5d1675cfaec5" />
<img width="1731" height="2376" alt="Screenshot_18-6-2026_185439_192 168 100 77" src="https://github.com/user-attachments/assets/2bef8e8a-3404-44d7-8ddf-f7884b790fd6" />
<img width="1731" height="753" alt="Screenshot_18-6-2026_185341_192 168 100 77" src="https://github.com/user-attachments/assets/3f7bb082-de60-4023-9e83-39eb203294d1" />
<img width="1731" height="1648" alt="Screenshot_18-6-2026_19637_192 168 100 77" src="https://github.com/user-attachments/assets/a134b56f-d371-4e3a-8b44-9e603aea71b4" />
<img width="1731" height="2563" alt="Screenshot_18-6-2026_19513_192 168 100 77" src="https://github.com/user-attachments/assets/b86a7f96-e682-4e01-87cd-842b4b85be4b" />
<img width="1731" height="1999" alt="Screenshot_18-6-2026_19441_192 168 100 77" src="https://github.com/user-attachments/assets/731c26ec-1442-4a96-88a0-bb9513163125" />
<img width="1731" height="1590" alt="Screenshot_18-6-2026_19116_192 168 100 77" src="https://github.com/user-attachments/assets/6e2405e8-f86d-4c24-a946-c7b1300aab5b" />
<img width="1731" height="4597" alt="Screenshot_18-6-2026_1939_192 168 100 77" src="https://github.com/user-attachments/assets/9ed2e9cf-f182-4b68-99ef-3cd5a4723509" />
<img width="1315" height="925" alt="Screenshot 2026-06-18 at 19-10-17 Vendly" src="https://github.com/user-attachments/assets/bdfa4fb9-2706-4ec2-8143-aaa8a6855238" />
<img width="1321" height="1827" alt="Screenshot 2026-06-18 at 19-09-35 Vendly" src="https://github.com/user-attachments/assets/e4bdf038-f58d-4381-8cb5-37215e891bcd" />
<img width="1332" height="1584" alt="Screenshot 2026-06-18 at 19-09-09 Vendly" src="https://github.com/user-attachments/assets/24a0520b-a17d-4a2a-a06d-4553ddbc743c" />
<img width="1315" height="925" alt="Screenshot 2026-06-18 at 19-08-41 Vendly" src="https://github.com/user-attachments/assets/dc307b04-8493-4473-9feb-2035793b998e" />
<img width="1315" height="516" alt="Screenshot 2026-06-18 at 19-06-06 Vendly" src="https://github.com/user-attachments/assets/c97ffd7d-1382-41aa-a97a-698d5132cf3d" />
<img width="1731" height="3418" alt="Screenshot_18-6-2026_185610_192 168 100 77" src="https://github.com/user-attachments/assets/346119d3-3d81-4096-956f-afd3dfdcdf9d" />
<img width="1731" height="1901" alt="Screenshot_18-6-2026_185540_192 168 100 77" src="https://github.com/user-attachments/assets/c1fd3a0e-f0a1-4c81-9e15-5b029c7bfbea" />
<img width="1731" height="1901" alt="Screenshot_18-6-2026_185524_192 168 100 77" src="https://github.com/user-attachments/assets/d2d2d880-15f3-49e0-bf73-2ca40cd4b93c" />


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
We are open to negotiation. Message **[@vendlydevs](https://t.me/vendlydevs)** on Telegram to discuss pricing options, view the live `.onion` demo, and secure your license.
