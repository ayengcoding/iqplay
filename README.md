# iQPlay TMDB — Next-Gen Blogger Streaming Theme

<div align="center">

<img src="banner.jpg" alt="iQPlay TMDB Theme Banner" width="760" style="max-width: 100%; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.35);" />

<br><br>

[![Theme Platform](https://img.shields.io/badge/Platform-Blogger_XML-FF5722?style=for-the-badge&logo=blogger&logoColor=white)](https://blogger.com)
[![Version](https://img.shields.io/badge/Version-v2.4.0-9333ea?style=for-the-badge&logo=git&logoColor=white)](https://github.com/ayengcoding/iqplay/releases)
[![License](https://img.shields.io/badge/License-Commercial-059669?style=for-the-badge&logo=gumroad&logoColor=white)](https://ayengstore.gumroad.com/l/iqplay)
[![Live Demo](https://img.shields.io/badge/Live_Demo-iqplayofficial.blogspot.com-E50914?style=for-the-badge&logo=googlechrome&logoColor=white)](https://iqplayofficial.blogspot.com/)
[![Live Docs](https://img.shields.io/badge/Live_Docs-GitHub_Pages-2563eb?style=for-the-badge&logo=githubpages&logoColor=white)](https://ayengcoding.github.io/iqplay/)

<p align="center">
  <b>High-performance, dark-slate video on-demand Blogger theme powered by TMDb v3 REST API, dynamic multi-server failover streaming, Supabase cloud user system, and interactive season/episode navigation.</b>
</p>

<!-- Social & Community Connect Badges -->
<p align="center">
  <a href="https://t.me/ayengcodingofficial" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Telegram_Community-24A1DE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Official Group" />
  </a>
  <a href="https://t.me/ayeng_coding" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Telegram_Channel-24A1DE?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel" />
  </a>
  <a href="https://www.facebook.com/acohcayeng" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Facebook_Profile-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook Profile" />
  </a>
  <a href="https://www.instagram.com/acoh_cariel/" target="_blank" rel="noopener">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://github.com/ayengcoding" target="_blank" rel="noopener">
    <img src="https://img.shields.io/github/followers/ayengcoding?label=Followers&style=for-the-badge&color=2563eb&logo=github" alt="GitHub Followers" />
  </a>
</p>

---

</div>

## 📌 Project Overview

**iQPlay TMDB** transforms any standard Google Blogger website into a lightning-fast, full-featured video streaming portal. By fetching real-time metadata, backdrop artworks, cast directories, and episode guides on-the-fly via the TMDb REST API v3, webmasters can run an entire movie and TV series library without requiring VPS hosting, heavy SQL databases, or complex server management.

- **Theme Name:** iQPlay TMDB
- **Current Version:** v2.4.0 (Production Stable)
- **Target Platform:** Google Blogger (Blogspot XML Engine)
- **Author:** Ayeng Coding
- **Repository:** [https://github.com/ayengcoding/iqplay](https://github.com/ayengcoding/iqplay)
- **Live Documentation Portal:** [https://ayengcoding.github.io/iqplay/](https://ayengcoding.github.io/iqplay/)
- **Live Interactive Demo:** [https://iqplayofficial.blogspot.com/](https://iqplayofficial.blogspot.com/)
- **Official Store / License:** [https://ayengstore.gumroad.com/l/iqplay](https://ayengstore.gumroad.com/l/iqplay)

---

## 🧭 Interactive Documentation Table of Contents

Navigate the complete developer guide available in the interactive [GitHub Pages Documentation Portal](https://ayengcoding.github.io/iqplay/):

1. **[Get Started](https://ayengcoding.github.io/iqplay/#intro)**
   - [Introduction to Theme Core](https://ayengcoding.github.io/iqplay/#intro)
   - [Quickstart & 4-Step Installation](https://ayengcoding.github.io/iqplay/#quickstart)
   - [Import Demo Posts (feed.atom)](https://ayengcoding.github.io/iqplay/#demo-posts)
   - [Essential Pages Setup (Player, Details, Library)](https://ayengcoding.github.io/iqplay/#essential-pages)
2. **[General Information](https://ayengcoding.github.io/iqplay/#license-system)**
   - [License System & Anti-Theft Domain Lock](https://ayengcoding.github.io/iqplay/#license-system)
   - [Development & Version Changelog](https://ayengcoding.github.io/iqplay/#changelog)
3. **[Dynamic Integrations](https://ayengcoding.github.io/iqplay/#tmdb-config)**
   - [The Movie Database (TMDb) API v3 Engine](https://ayengcoding.github.io/iqplay/#tmdb-config)
   - [Supabase User Accounts & Realtime Watchlist Sync](https://ayengcoding.github.io/iqplay/#supabase-auth)
   - [Multi-Server Failover Video Players](https://ayengcoding.github.io/iqplay/#multi-server)
   - [Realtime Stats, View Counters & Nested Comments](https://ayengcoding.github.io/iqplay/#counter-comments)
4. **[Ecosystem & Tools](https://ayengcoding.github.io/iqplay/#shortcode-builder)**
   - [Interactive Homepage Widget Shortcode Generator](https://ayengcoding.github.io/iqplay/#shortcode-builder)
   - [Blogger Post Schema Creator](https://ayengcoding.github.io/iqplay/#post-creator)
   - [Diagnostic Center & Troubleshooting FAQ](https://ayengcoding.github.io/iqplay/#troubleshooting)
5. **[Community & Support](https://ayengcoding.github.io/iqplay/#community)**
   - [Official Community Channels & Direct Support Contacts](https://ayengcoding.github.io/iqplay/#community)

---

## ⚡ Real Theme Code & Language Stack Breakdown

| Technology / Language | Distribution Badge | Share (%) | Source Lines | Primary Architecture Responsibility |
| :--- | :--- | :---: | :---: | :--- |
| **Modular JavaScript (ES6+)** | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | 62.5% | 3,666 Lines | Client-side TMDb REST fetcher, Supabase authentication client, multi-server video switcher, season/episode router, and local storage caching. |
| **Blogger XML Layout Engine** | ![Blogger XML](https://img.shields.io/badge/Blogger_XML-FF5722?style=flat-square&logo=blogger&logoColor=white) | 20.5% | 1,202 Lines | Templating tags (`<b:includable>`, `<b:widget>`, `<data:post.*>`), conditional page routing, metadata injection, and gadget sections. |
| **CSS3 & Responsive Styles** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | 17.0% | 994 Lines | Dual light/dark theme variables, fluid CSS grid, sticky 2-tier navigation bars, off-canvas slide drawer, and custom dark scrollbars. |

---

## 🚀 Theme Core Features

- 🎬 **Instant TMDb Metadata Injection:** No manual synopsis typing. Enter a movie or TV TMDb ID and the theme loads posters, backdrops, ratings, release years, cast carousels, and trailers on-the-fly.
- 🔄 **Multi-Server Video Failover:** Built-in support for SuperEmbed, 2Embed, VidSrc, AutoEmbed, plus custom direct MP4/HLS streams (`.m3u8`).
- 🔐 **Supabase Cloud User Engine:** Cloud login and registration allowing visitors to maintain a personalized watchlist and playback history across devices.
- 📱 **Flawless Mobile UX:** Off-canvas slide navigation drawer, touch-swipe subnav pill bar with hidden scrollbars, responsive video players, and live search modal with keyboard shortcuts (<kbd>Ctrl+K</kbd>).
- 🌓 **Dual Light / Dark Mode Engine:** Instant theme switching with auto-persisted preference saved in `localStorage`.
- 🛡️ **Anti-Theft Domain Lock:** Integrated client-side domain authorization preventing unauthorized duplication of your licensed purchase.

---

## 🌐 Connect & Official Community Links

Reach out directly for technical assistance, domain registration approvals, custom modifications, or theme updates:

- **Author Telegram:** [@ayengcoding](https://t.me/ayengcoding) *(Direct Support)*
- **Telegram Broadcast Channel:** [@ayeng_coding](https://t.me/ayeng_coding) *(Announcements & Patches)*
- **Telegram Community Group:** [@ayengcodingofficial](https://t.me/ayengcodingofficial) *(Community Discussions)*
- **Facebook Profile:** [facebook.com/acohcayeng](https://www.facebook.com/acohcayeng)
- **Instagram Profile:** [@acoh_cariel](https://www.instagram.com/acoh_cariel/)
- **GitHub Organization:** [@ayengcoding](https://github.com/ayengcoding)
- **Gumroad Digital Store:** [ayengstore.gumroad.com](https://ayengstore.gumroad.com)

---

## 📄 License & Intellectual Property

Copyright &copy; 2026 Ayeng Coding. All rights reserved.  
Distributed under the official Commercial End User License Agreement (EULA). One license purchase authorizes deployment on one single active public domain name. Commercial resale or redistribution of source files without written authorization is strictly prohibited.
