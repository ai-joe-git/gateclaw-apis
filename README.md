# GateClaw API Explorer

A modern, beautiful web interface to explore curated APIs for GateClaw - the Resident AI Entity.

![GateClaw API Explorer](https://img.shields.io/badge/GateClaw-API%20Explorer-00dc82?style=for-the-badge)

## 🎯 Overview

This repository contains a static website that browses **65+ curated APIs** selected from the [public-apis/public-apis](https://github.com/public-apis/public-apis) repository (~1,400 total APIs) for potential integration into GateClaw.

## ✨ Features

- **🔍 Live Search** - Filter APIs by name, description, or category
- **🏷️ Tier Filters** - Browse by integration priority (Tier 1/2/3)
- **📁 Category Navigation** - Explore APIs across 50+ categories
- **🎨 Modern UI** - Dark cyberpunk theme with neon accents
- **📱 Responsive** - Works on desktop and mobile
- **⚡ Fast** - Pure static HTML/CSS/JS, no build required

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gateclaw-apis.git
cd gateclaw-apis
```

2. Open `index.html` in your browser:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

That's it! No build step, no dependencies.

## 📊 API Tiers

### Tier 1 - Immediate Integration (High Value, Low Friction)
- No auth or simple apiKey
- HTTPS + CORS support
- Direct conversational value
- Examples: OpenWeather, Chuck Norris API, Cat Facts, NASA API

### Tier 2 - Strategic Integration (Medium Complexity, High Utility)
- More setup required
- Higher utility for specific use cases
- Examples: CoinGecko, NewsAPI, HaveIBeenPwned, VirusTotal

### Tier 3 - Nice-to-Have (Specialized Use Cases)
- Specialized functionality
- Lower priority but still valuable
- Examples: Sports APIs, Food APIs, Test Data generators

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom variables, animations, grid layout
- **Vanilla JavaScript** - No frameworks, pure JS
- **Google Fonts** - Inter + JetBrains Mono

## 📁 Structure

```
gateclaw-apis/
├── index.html          # Main application (HTML + CSS + JS)
├── .gitignore          # Git ignore rules
├── README.md           # This file
└── .github/            # GitHub metadata (auto-generated)
```

## 🎨 Design System

### Colors
- Primary: `#00dc82` (Neon Green)
- Secondary: `#00ff9d` (Bright Green)
- Background: `#0a0a0f` (Dark Space)
- Card: `#1a1a25` (Dark Purple)

### Typography
- Headings: `Inter` (Sans-serif)
- Code/Meta: `JetBrains Mono` (Monospace)

## 🔗 Links

- **Source**: [public-apis/public-apis](https://github.com/public-apis/public-apis)
- **GateClaw**: Resident AI Entity documentation
- **Deploy**: [Vercel](https://vercel.com)

## 📄 License

MIT License - See [LICENSE](LICENSE) file

## 🤝 Contributing

This is a curated list for GateClaw integration. To suggest new APIs or improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

**Built for GateClaw** - Resident AI Entity | March 2026
