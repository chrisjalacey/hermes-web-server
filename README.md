# Bilbao & Basque Country — Authentic Non-Tourist Guide

A comprehensive, modular HTML guide for travellers seeking authentic Basque experiences beyond the tourist trail. Built with NotebookLM deep research and designed for offline/online use.

## 🌐 Live Demo

Open `bilbao-guide.html` in a browser, or serve locally:

```bash
cd web-server
python3 -m http.server 8000
# Visit http://localhost:8000/bilbao-guide.html
```

## 📁 Site Structure

```
bilbao-guide.html           # Main landing page (7 navigation cards)
├── neighbourhoods.html     # 7 Bilbao barrios + Getxo/Donostia areas
├── day-trips.html          # 8 itineraries with logistics
├── culture.html            # 7 cultural experience types
├── dietary-reference.html  # Filterable table (40+ venues)
├── practical-tips.html     # August calendar, transport, safety
├── wineries.html           # 17 wineries across 3 DOs
└── restaurants/
    ├── index.html          # 10 cuisine categories
    ├── pintxos.html        # 5 bars
    ├── traditional.html    # 4 asadores/sidrerías
    ├── seafood.html        # 3 venues (Zarate ⭐)
    ├── modern-basque.html  # 4 venues (6 Michelin stars)
    ├── asian.html          # Kimtxu (Michelin Guide)
    ├── italian-gf.html     # 2 dedicated GF venues
    ├── bakeries.html       # Magora & Kuki (100% GF)
    └── breakfast.html      # 3+ venues
```

## ✨ Key Features

| Feature | Details |
|---------|---------|
| **Modular HTML** | 17 files, no build step, works offline |
| **Dietary badges** | GF (100% Dedicated / Friendly / Aware / Limited) + Pescatarian (✓/✓✓/✓✓✓) |
| **Filterable table** | Vanilla JS, zero dependencies |
| **Distance & transport** | Every venue: km/min from Calle García Salazar + Metro/bus/taxi |
| **Website links** | Clickable official sites + "Book visit" CTAs |
| **August-specific** | Semana Grande (Aug 8–15), Aste Nagusia (Aug 22–30), Assumption (Aug 15) |
| **UK English** | `lang="en-GB"`, neighbourhood/favourite/theatre/centre/customise |
| **Responsive** | CSS Grid/Flex, mobile-first, no frameworks |

## 🍷 Wineries Covered (17)

| Region | Wineries |
|--------|----------|
| **Rioja Alavesa** | Marqués de Riscal, Ysios, Baigorri, El Fabulista, Artadi, Remelluri, LAN, CVNE/Viña Real |
| **Getariako Txakolina** | Txomin Etxaniz, Ameztoi, Gaintza, Talai Berri, Hiruzta |
| **Bizkaiko Txakolina** | Gorka Izagirre, Txakoli Simón, Itsasmendi, Doniene Gorrondona |

Unique experiences: e-bike tours, horseback riding, hot air balloon, vinotherapy, blending workshops, harvest participation, vineyard picnics, cellar concerts, photography tours, stargazing.

## 🍽️ Restaurants (40+)

Organised by cuisine with Google ratings, hours, dietary flags, reservation lead times, and Michelin status.

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/chrisjalacey/hermes-web-server.git
cd hermes-web-server

# Serve locally
python3 -m http.server 8000
# Open http://localhost:8000/bilbao-guide.html
```

Or simply open `bilbao-guide.html` directly in any browser.

## 🛠️ Tech Stack

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, Grid/Flex, mobile-first
- **Vanilla JS** — Single filterable table (dietary-reference.html)
- **No dependencies** — Zero build, zero runtime deps

## 📚 Research Sources

- NotebookLM deep research (155+ sources)
- Google Maps reviews, Michelin Guide, Repsol Guide
- FACE Celiac Association certification data
- Basque wine DO websites (Rioja Alavesa, Getariako Txakolina, Bizkaiko Txakolina)
- Local gastronomy blogs & media

## 📄 License

MIT — Free to use, adapt, and share.

---

**Last updated:** July 2026  
**Reference point:** Calle García Salazar, Bilbao (distance calculations)