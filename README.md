# 🌻 Sunflower Land Master Guide

> **The definitive community-made profit guide for Sunflower Land.**
> From Noob to Pro — Level 1 to Endgame.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square&logo=github)
![Language](https://img.shields.io/badge/Language-EN%20%7C%20ES-blue?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.0.0-gold?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 🌐 Live Site

**👉 [View the Guide](https://andcamac.github.io/sunflower-land-guide)**



---

## 📖 What's Inside

| Feature | Description |
|---------|-------------|
| 🗺️ **Interactive Roadmap** | 6 collapsible stages from Level 1 to Level 51+ with XP bars, tasks & pro tips |
| 🐄 **Cow Dairy Deep Dive** | Live profit calculator with sliders + optimal skill build |
| 📅 **Daily Checklist** | 23 tasks across 3 sessions with priority tags & progress bars |
| 🌍 **Seasonal Strategy** | 4 clickable season tabs with crops, events & power moves |
| 💰 **Profit Rankings** | Market-adjusted table of every income source |
| 🌐 **EN / ES** | Full English & Spanish toggle, saved in localStorage |

---

## 🚀 Deploy to GitHub Pages (5 minutes)

### Option 1 — GitHub Web Interface (Easiest)

1. Click **"Use this template"** or **fork** this repository
2. Go to your repo → **Settings** → **Pages**
3. Under **Source**, select `main` branch → `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://YOUR-USERNAME.github.io/sunflower-land-guide`

### Option 2 — Git CLI

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/sunflower-land-guide.git
cd sunflower-land-guide

# Make changes, then push
git add .
git commit -m "Update guide"
git push origin main
```

GitHub Pages will automatically rebuild on every push to `main`.

---

## 📁 File Structure

```
sunflower-land-guide/
├── index.html              ← Main interactive website (self-contained)
├── Sunflower_Land_Profit_Bible.md  ← Full Notion-ready guide
├── README.md               ← This file
├── LICENSE                 ← MIT License
└── .github/
    └── workflows/
        └── pages.yml       ← Auto-deploy GitHub Actions workflow
```

---

## ✏️ How to Edit

The entire site is **one self-contained `index.html` file** — no build tools, no npm, no dependencies. Just open it in any text editor.

### Adding translations
Find the `i18n` object in the `<script>` tag at the bottom of `index.html`:
```javascript
const i18n = {
  en: { "key": "English text" },
  es: { "key": "Texto en español" }
}
```
Add a new language block following the same pattern, then add a button in the `lang-toggle` div.

### Updating prices / data
Search for `FLOWER/WEEK` or `$0.05` in `index.html` to find all price references.

---

## 📊 Guide Coverage

- ✅ Farming (all seasonal crops + Greenhouse)
- ✅ Animals (Cows, Chickens, Sheep — full Barn & Hen House mechanics)
- ✅ Mining (Stone → Iron → Gold → Crimstone → Oil → Obsidian chain)
- ✅ Fishing (Marine Marvels, bait, Full Moon strategy)
- ✅ Cooking (all 5 buildings, top XP/hour foods)
- ✅ NPC Deliveries (all 6 FLOWER NPCs, Chef Apron stacking)
- ✅ Factions (Marks economy, Eldric shop, joining strategy)
- ✅ Minigames (all 6 minigames, Marks efficiency ranking)
- ✅ Flowers & Bees (Beehives, Bee Swarm, NPC gifts → Luxury Keys)
- ✅ Treasure Island (digging grid, streak rewards, Sand Drill)
- ✅ Love Island (Love Charms → FLOWER conversion)
- ✅ Pets & Shrines (XP system, Stag Shrine, quadratic leveling)
- ✅ Seasonal Weather (Tornado, Tsunami, Great Freeze, Bountiful Harvest)
- ✅ Auctions & Megastore (Chapter Tickets, blind bidding strategy)
- ✅ Marketplace (10% tax, withdrawal tax, listing limits, arbitrage)
- ✅ Profit Calculator (interactive, cow-based, skill-adjusted)

---

## 🤝 Contributing

Pull requests are welcome! If you find outdated data or new mechanics:

1. Fork the repo
2. Create a branch: `git checkout -b update/new-mechanic`
3. Edit `index.html` and/or `Sunflower_Land_Profit_Bible.md`
4. Open a PR with a description of what changed

---

## ⚠️ Disclaimer

This is a **community-created guide**, not affiliated with Thought Farm Studio. Game mechanics and token prices change frequently — always cross-reference with the [official docs](https://docs.sunflower-land.com) and [SFL Wiki](https://wiki.sfl.world).

FLOWER price estimates based on ~$0.05 (May 2026). Earnings are estimates, not guarantees.

---

## 🔗 Useful Links

- 📚 [Official Docs](https://docs.sunflower-land.com)
- 🌐 [SFL World Tools](https://sfl.world)
- 📖 [SFL Wiki](https://wiki.sfl.world)
- 💬 [Discord](https://discord.com/invite/sunflowerland)
- 🛒 [OpenSea — SFL NFTs](https://opensea.io/collection/sunflower-land)

---

## 📄 License

MIT — free to use, share and modify. See [LICENSE](LICENSE).

---

<div align="center">
  🌻🌻🌻🌻🌻<br/>
  <strong>Made with ❤️ for the Sunflower Land community</strong><br/>
  🌻🌻🌻🌻🌻
</div>
