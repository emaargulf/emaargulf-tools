<div align="center">
  <img src="https://emaargulf.github.io/emaargulf-branding/assets/logos/logo-icon-dark.svg" alt="Emaar Gulf Icon" width="100" />
  <br/><br/>
  <h1>Emaar Gulf | Tools Portal</h1>
  <h3>Official Web Applications & Corporate Utilities</h3>
  <p><i>Single Source of Truth for Human Developers & Automated Systems</i></p>
</div>

---

> **System Status:** Production / Active  
> **Environment:** Vanilla HTML/CSS/JS (Zero-Dependencies)  
> **Target:** iOS, Android, Windows, macOS  

This repository serves as the central CDN and hosting environment for Emaar Gulf Engineering Consultants' web tools and utilities. It is designed with a strict focus on mobile responsiveness, high performance, and corporate brand alignment (Brand Navy `#0B1D35` & Brand Gold `#C5A059`).

---

## 🚀 Live Production Environments

| Application Module | Description | Production URL |
| :--- | :--- | :--- |
| **Tools Hub** | Main landing page and directory for corporate utilities. | [Access Hub](https://emaargulf.github.io/emaargulf-tools/tools/index.html) |
| **Eid Al-Fitr App** | Interactive, audio-enabled web application for client distribution. | [Launch Portal](https://emaargulf.github.io/emaargulf-tools/eid_al-fitr/) |

---

## 📂 System Architecture

The repository is organized into isolated, purpose-built modules to ensure modular scalability without code conflicts.

```text
emaargulf-tools/
│
├── tools/                      <-- Utilities Core
│   ├── index.html              <-- Main Tools Dashboard / Routing Hub
│   └── README.md               <-- System Documentation (This File)
│
└── eid_al-fitr/                <-- Marketing & Interactive Campaigns
    ├── index.html              <-- Main App Logic, Animations & UI
    ├── og-image.jpg            <-- Open Graph (WhatsApp/Social) Thumbnail
    ├── ambient.mp3             <-- Background atmospheric audio
    ├── chime.mp3               <-- Interaction audio asset
    ├── hum.mp3                 <-- Ambient interaction audio
    └── swoosh.mp3              <-- Transition audio asset
