# 🎙️ NirobTech Podcast Suite

A complete suite of tools for **Podcast Creators, Founders, and Agencies** – designed to grow audiences, automate outreach, optimize SEO, and integrate with the future of Web3.

> 🚀 Built by [MUH Nirob](https://github.com/nirobtech), Founder of [Nirob Tech](https://github.com/nirobtech/nirobtech)  
> 💼 Contact: [nirobtch@gmail.com](mailto:nirobtch@gmail.com)

---

## 🧠 Overview

**Podcast** is an open-source initiative to empower podcast owners and digital broadcasters with high-performance tools:

| Feature                 | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🌐 Landing Page System | Fast, PHP-based SEO-optimized landing pages with high-conversion templates  |
| 📬 Email Engine        | CLI+GUI email automation system for 300+ daily podcast outreach campaigns   |
| 🎯 SEO Framework       | Structured data, meta tags, sitemap & indexing tools for podcasts           |
| 🧠 Guest/Sponsor Match | Match guests & sponsors using AI + email automation (coming soon)           |
| 🧩 NFT/Token Access    | Web3-based episode unlocks or subscriber NFT integration (planned)          |

---

## 🧱 Architecture

```
📦 Podcast/
├── public/
│   ├── index.php              # Dynamic Landing Page for Podcast Services
│   ├── assets/                # CSS, JS, images
├── email/
│   ├── campaign-templates/    # Outreach email samples (HTML/Text)
│   └── automation-scripts/    # Shell scripts for sending emails (SMTP/API)
├── seo/
│   ├── sitemap.xml            # Auto-generated podcast sitemap
│   ├── meta-schema.jsonld     # Podcast schema for SEO (Google Podcasts, etc.)
├── web3/
│   └── nft-access.json        # Future: Smart contract logic for Web3 access
├── docs/
│   └── README.md              # This file
```

---

## 🔥 Core Features

### 🎧 1. Dynamic Landing Pages
- Built in `PHP`, deployable via CPanel or VPS
- Pre-loaded with SEO keywords (e.g. `podcast promotion USA`, `grow podcast`)
- Localized target: `USA`, `UK`, `Canada`, `Germany`, `Australia`

### 📩 2. Email Outreach System
- CLI + GUI (optional via Cockpit or PHP Dashboard)
- SMTP-ready (Postal, Mailgun, SendGrid integration planned)
- Bounce handling, auto-unsubscribe, and A/B testing support

### 🧠 3. Podcast SEO Engine
- Schema.org markup for episodes
- Auto sitemap generation
- Keywords for 2025–2030 (AI podcast, NFT podcast, global growth, etc.)

### 🧩 4. Web3 & NFT Integration (Planned)
- Token-gated episode unlocks
- Mint NFTs for podcast guests
- Connect MetaMask and decentralized identity

---

## 🌍 Who It's For

- **🎙 Podcast Owners** who want international growth
- **📢 Digital Agencies** offering podcast marketing
- **🧑‍💻 Developers** building podcast tech
- **💼 Investors** looking to back next-gen podcast platforms

---

## 🛠️ Tech Stack

| Layer              | Tools Used                                 |
|-------------------|---------------------------------------------|
| Frontend          | HTML5, CSS3, Bootstrap, Vanilla JS          |
| Backend           | PHP 8, Shell, Bash                          |
| Hosting           | CPanel, Ubuntu Server 24.04, Cloudflare     |
| Email Layer       | Postal (OSS), Mailgun, Gmail API (planned) |
| DevOps/CLI        | Termux, Git, UFW, Cockpit, htop, curl       |
| Web3 Layer        | MetaMask, IPFS, ERC-721/ERC-1155 (future)   |

---

## 📈 Keywords We're Targeting

> Latest SEO Research (Updated Monthly)

```
podcast promotion services  
grow podcast USA UK Canada  
guest outreach tool  
podcast marketing automation  
podcast SEO agency  
how to monetize podcast 2025  
AI for podcasting  
Web3 podcast platforms  
```

---

## 📌 Roadmap

| Feature                   | Status         |
|---------------------------|----------------|
| Landing Page Deployment   | ✅ Completed    |
| 300 Email/Day CLI Script  | 🔄 In Progress |
| Cockpit GUI Setup         | ✅ Completed    |
| NFT Podcast Unlock Tool   | 🔜 Planned      |
| AI Guest Matching Engine  | 🔜 Planned      |

---

## 🚀 Deployment Instructions

```bash
git clone https://github.com/nirobtech/Podcast.git
cd Podcast/public

# If on Ubuntu server:
sudo apt install apache2 php
cp -r * /var/www/html/
sudo systemctl restart apache2

# Or upload to /public_html/ via CPanel
```

---

## 🤝 Contributing

We welcome contributors! Open a pull request or issue here:  
👉 [https://github.com/nirobtech/Podcast](https://github.com/nirobtech/Podcast)

---

## 👤 Maintained by

**MUH Nirob**  
📧 [nirobtch@gmail.com](mailto:nirobtch@gmail.com)  
🔗 GitHub: [nirobtech](https://github.com/nirobtech)  
🔗 Project Home: [nirobtech/nirobtech](https://github.com/nirobtech/nirobtech)

---

## 🔐 License

This project is licensed under the **MIT License** – free to use, remix, and build upon with proper credit.

---

> “Build powerful tools to protect the voice of independent creators.”  
> — MUH Nirob | Nirob Tech
