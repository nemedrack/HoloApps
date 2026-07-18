# Holo Apps

A collection of personal Hololive-themed web applications, all in one place.

## 🌐 Live Site

Visit: [nemedrack.github.io/HoloApps](https://nemedrack.github.io/HoloApps)

## 📱 Apps Included

### 🎡 **Holo Roulette**
Spin the wheel for giveaways and random selections. Perfect for tournaments and community events.
- Path: `/roulette/`

### ⏱️ **Holo Round**
Tournament round timer and podium display. Show live results with player names and deck information.
- Path: `/round/`

### 🏆 **Holo TOP**
Hololive trading card game portfolio. Browse collections and explore the card universe.
- Path: `/top/`

## 🚀 Local Development

Since these are all static HTML files, just open the files directly or use a simple HTTP server:

```bash
# Using Python (3.x)
python -m http.server 8000

# Using Node.js http-server
npx http-server

# Then visit: http://localhost:8000
```

## 📁 Project Structure

```
HoloApps/
├── index.html          # Landing page with navigation
├── roulette/
│   └── index.html      # Roulette app
├── round/
│   └── index.html      # Tournament timer app
├── top/
│   └── index.html      # Card portfolio app
├── .github/
│   └── workflows/
│       └── pages.yml   # GitHub Pages auto-deploy
├── .gitignore
└── README.md
```

## 🔧 How to Update

1. Make changes to any app locally
2. Test by opening `index.html` or running a local server
3. Commit and push to GitHub
4. GitHub Pages automatically deploys on push to `main`/`master`

## 🎨 Styling

All apps use the Hololive purple theme:
- Primary Dark: `#3D2E5E`
- Primary Medium: `#4A3F7F`
- Primary Light: `#9B8DC6`
- Accent Light: `#D4C5E2`

## 📝 Notes

- Each app is self-contained and can work independently
- No build step required - all static files
- Fully responsive and mobile-friendly
- GitHub Pages deployment is automatic via workflow

## 🔗 Links

- GitHub: https://github.com/nemedrack/HoloApps
- Hololive: https://hololive.tv/

---

Made with 💜 for Hololive fans
