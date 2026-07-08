# Haithem Haraga — Portfolio & Browser Game Arcade

A black-and-purple personal site with **12 playable browser games** built in pure vanilla
JavaScript and the Canvas API — no engines, no frameworks, no build step. Just open
`index.html`.

**Live:** https://haithemharaga.com

## 🎮 Games
Snake · 2048 · Brick Breaker · Memory Match · Reaction Test · Tetris · Flappy Purple ·
Minesweeper · Tic-Tac-Toe (unbeatable minimax AI) · Simon Says · Whack-a-Mole ·
+ a secret **Pong vs AI** (unlock with the Konami code ↑↑↓↓←→←→BA).

High scores save locally in your browser.

## ✨ Features
- Animated particle-network background (press **P** to toggle)
- Glowing cursor, gradient/typing hero, scroll-reveal animations
- Fully responsive + touch controls, respects `prefers-reduced-motion`
- SEO: Open Graph + Twitter cards, JSON-LD structured data, `sitemap.xml`, `robots.txt`
- Installable PWA (`site.webmanifest`)

## 🛠 Tech
Single self-contained `index.html` (HTML + CSS + JS). Font Awesome via CDN.

## Structure
```
index.html          # the whole site + all games
CNAME               # custom domain for GitHub Pages
robots.txt          # search-engine crawl rules
sitemap.xml         # sitemap for Search Console
site.webmanifest    # PWA manifest
images/             # favicon, og-image, screenshots
```

© 2026 Haithem Haraga
