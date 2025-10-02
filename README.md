# 🏎️ F1 Singapore GP 2025 Schedule

A sleek, dark-themed web application for viewing the complete Formula 1 Singapore Airlines Singapore Grand Prix 2025 schedule. Built as a Cloudflare Worker with automatic event tracking, live notifications, and countdown timer.

## ✨ Features

- **📅 3-Day Schedule** - Friday, Saturday, Sunday tabs with all events
- **⏱️ Live Countdown** - Timer for the first F1 practice session
- **🔔 Smart Notifications** - Auto-notify when new events go live (only if you've switched tabs)
- **🎯 Auto-Scrolling** - Automatically switches to current day and scrolls to live event
- **🕐 Real-Time Updates** - Checks every minute for event changes
- **📱 Mobile Optimized** - Fully responsive with Safari-safe bottom notifications
- **🌙 Dark Theme** - Racing-inspired dark mode with F1 red accents

## 🚀 Deployment

### Deploy to Cloudflare Pages

1. **Clone this repository:**
   ```bash
   git clone <your-repo-url>
   cd f1schedule
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Deploy to Cloudflare Pages:**
   - Push to GitHub
   - Connect your GitHub repo to Cloudflare Pages
   - Build command: (leave empty - no build needed)
   - Output directory: (leave empty)
   - The worker will automatically deploy

### Or Deploy with Wrangler

```bash
npm run deploy
```

## 🛠️ Development

Run locally:
```bash
npm run dev
```

Visit `http://localhost:8787` to see the app.

## 📋 Event Schedule

The schedule includes:

**Friday, October 3rd**
- Porsche Carrera Cup Asia events
- F1 Academy Practice & Qualifying
- Formula 1 Practice Sessions 1 & 2
- Paddock Club experiences

**Saturday, October 4th**
- Support race qualifying and races
- Formula 1 Practice Session 3
- Formula 1 Qualifying Session

**Sunday, October 5th**
- Support races
- Drivers' Parade
- National Anthem
- **Formula 1 Grand Prix** 🏁

## 🎨 Tech Stack

- **Cloudflare Workers** - Serverless edge computing
- **Vanilla JavaScript** - No frameworks, pure performance
- **CSS3** - Modern styling with animations
- **Singapore Time (UTC+8)** - All times in local timezone

## 📄 License

This project is open source and available under the MIT License.

## ⚠️ Disclaimer

This page is not affiliated with, endorsed by, sponsored by, or connected to Formula One Licensing BV, Formula 1®, FORMULA 1, F1, the F1 logo, FIA FORMULA ONE WORLD CHAMPIONSHIP, Singapore GP Pte. Ltd., the Formula 1 Singapore Airlines Singapore Grand Prix 2025, or any official parties related to the event. All trademarks and logos mentioned are the property of their respective owners and are used here without permission.

## 💝 Support

If you find this app useful, consider [buying me a coffee](https://paypal.me/nastasiu/15eur)!

---

© 2025 [websqu.ad](https://websqu.ad) - a brandsquad oü division. All rights reserved.
