<div align="center">

<!-- HERO BANNER -->
<img src="https://obscuraworks.com/og-banner.png" alt="Obscuraworks API" width="100%" />

<br/>

# ⚡ Obscuraworks API

**The all-in-one REST API platform for developers.**  
Downloader · Search · AI · Tools · Fun — all under one key.

[![License](https://img.shields.io/badge/license-MIT-orange?style=flat-square)](LICENSE)
[![API Status](https://img.shields.io/badge/API-Online-brightgreen?style=flat-square)](https://docs.obscuraworks.com)
[![Free Tier](https://img.shields.io/badge/Free%20Tier-100%20Requests-blue?style=flat-square)](https://docs.obscuraworks.com/signup)
[![Docs](https://img.shields.io/badge/Docs-docs.obscuraworks.com-orange?style=flat-square)](https://docs.obscuraworks.com)

[📖 Documentation](https://docs.obscuraworks.com) · [🔑 Get API Key](https://docs.obscuraworks.com/signup) · [📋 Changelog](https://docs.obscuraworks.com/changelog) · [💬 Support](#-support)

</div>

---

## 🌐 What is Obscuraworks API?

**Obscuraworks** is a public REST API platform that gives developers instant access to powerful, production-ready endpoints — no complex setup, no servers to maintain.

Whether you're building a **WhatsApp bot**, a **Discord bot**, a **web app**, or a **mobile app**, Obscuraworks has the endpoints you need to ship fast.

> 🔗 **Base URL:** `https://api.obscuraworks.com`  
> 📚 **Full Docs:** [docs.obscuraworks.com](https://docs.obscuraworks.com)

---

## 🧩 API Categories

| Category | Description | Example Endpoints |
|---|---|---|
| 📥 **Downloader** | Download media from social platforms | Instagram, YouTube, TikTok, Facebook, Threads, Twitter/X |
| 🔍 **Search** | Search engines for content discovery | Anime, Lyrics, Movies, Books, News |
| 🤖 **AI** | AI-powered processing tools | Image Enhancer, Chatbot, Text Generator, Background Remover |
| 🧰 **Tools** | Developer utilities | QR Generator, URL Shortener, IP Lookup, Base64, OCR |
| 🎮 **Fun** | Entertainment & game APIs | Meme Generator, Trivia, Word Games, Random Quotes |

---

## 🚀 Quick Start

### 1. Get Your Free API Key

Sign up and receive **100 free requests** instantly:

```
https://docs.obscuraworks.com/signup
```

### 2. Whitelist Your IP

Visit your dashboard to whitelist your IP address:

```
https://docs.obscuraworks.com/dashboard/profile
```

### 3. Make Your First Request

Replace `YOUR_API_KEY` with your actual key and you're ready to go.

---

## 📦 Code Examples

### Instagram Reel Downloader

```js
/**
 * Obscuraworks API — Instagram Downloader
 * Docs: https://docs.obscuraworks.com/downloader/instagram
 */

const apiKey = "YOUR_API_KEY";
const targetUrl = "https://www.instagram.com/reel/DKeOUllzvC1/";

const response = await fetch(
  `https://api.obscuraworks.com/api/downloader/instagram?url=${encodeURIComponent(targetUrl)}`,
  {
    headers: {
      Authorization: `Bearer ${apiKey}`,
    },
  }
);

const result = await response.json();
console.log(result);
```

### YouTube Video Downloader

```js
/**
 * Obscuraworks API — YouTube Downloader
 * Docs: https://docs.obscuraworks.com/downloader/youtube
 */

const apiKey = "YOUR_API_KEY";
const targetUrl = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";

const response = await fetch(
  `https://api.obscuraworks.com/api/downloader/youtube?url=${encodeURIComponent(targetUrl)}`,
  {
    headers: {
      Authorization: `Bearer ${apiKey}`,
    },
  }
);

const result = await response.json();
console.log(result);
```

### TikTok Downloader (No Watermark)

```js
/**
 * Obscuraworks API — TikTok Downloader
 * Docs: https://docs.obscuraworks.com/downloader/tiktok
 */

const apiKey = "YOUR_API_KEY";
const targetUrl = "https://www.tiktok.com/@user/video/123456789";

const response = await fetch(
  `https://api.obscuraworks.com/api/downloader/tiktok?url=${encodeURIComponent(targetUrl)}`,
  {
    headers: {
      Authorization: `Bearer ${apiKey}`,
    },
  }
);

const result = await response.json();
console.log(result);
```

### QR Code Generator

```js
/**
 * Obscuraworks API — QR Generator
 * Docs: https://docs.obscuraworks.com/tools/qr
 */

const apiKey = "YOUR_API_KEY";
const text = "https://docs.obscuraworks.com";

const response = await fetch(
  `https://api.obscuraworks.com/api/tools/qr?text=${encodeURIComponent(text)}`,
  {
    headers: {
      Authorization: `Bearer ${apiKey}`,
    },
  }
);

const result = await response.json();
console.log(result.qr_url); // URL to the generated QR image
```

---

## 💳 Pricing Plans

| Plan | Requests/Month | Price |
|---|---|---|
| **Free** | 100 | $0 |
| **Starter** | 5,000 | See [pricing page](https://docs.obscuraworks.com/pricing) |
| **Pro** | 50,000 | See [pricing page](https://docs.obscuraworks.com/pricing) |
| **Enterprise** | Unlimited | See [pricing page](https://docs.obscuraworks.com/pricing) |

> 🔗 Full pricing details: [docs.obscuraworks.com/pricing](https://docs.obscuraworks.com/pricing)

---

## 📚 Documentation

Complete API reference with:
- ✅ All available endpoints
- ✅ Request parameters & response schemas  
- ✅ Authentication guide
- ✅ Rate limit information
- ✅ Error code reference
- ✅ Changelog & release notes

👉 **[docs.obscuraworks.com](https://docs.obscuraworks.com)**

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** this repository
2. **Add** new usage examples in your preferred language (Python, PHP, Go, etc.)
3. **Submit** a Pull Request

Help the community by showing how you use Obscuraworks in your projects!

---

## 🔗 Links

| Resource | URL |
|---|---|
| 🌐 Website | [obscuraworks.com](https://obscuraworks.com) |
| 📖 API Docs | [docs.obscuraworks.com](https://docs.obscuraworks.com) |
| 🔑 Sign Up | [docs.obscuraworks.com/signup](https://docs.obscuraworks.com/signup) |
| 📊 Dashboard | [docs.obscuraworks.com/dashboard](https://docs.obscuraworks.com/dashboard) |
| 📋 Changelog | [docs.obscuraworks.com/changelog](https://docs.obscuraworks.com/changelog) |
| 💻 GitHub | [github.com/obscuraworkscom](https://github.com/obscuraworkscom) |

---

## 💬 Support

Need help? Reach out through any channel:

| Platform | Contact |
|---|---|
| 💬 Telegram | [@NyxObscura](https://t.me/nyxobscura) |
| 📱 WhatsApp | [wa.me/6285183343636](https://wa.me/6285183343636) |
| 📧 Email | [support@obscuraworks.com](mailto:support@obscuraworks.com) |

---

<div align="center">

Made with 🔥 by the **Obscuraworks** team  
© 2025 Obscuraworks · [obscuraworks.com](https://obscuraworks.com)

</div>
