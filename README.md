# Notion Widget

A small collection of AI-generated ambient browser widgets designed to add a little personality to a Notion command center or personal dashboard.

These are fully self-contained HTML files with no build step or external dependencies. Each one runs straight in the browser and can be embedded in Notion.

## Included widgets

| File | What it is | Interaction |
| --- | --- | --- |
| `night-drive.html` | A rainy neon city at night with a moving car, reflective streets, glowing lights and a **COMMAND CENTER** sign in the sky. | Click to pause |
| `sakura-lake.html` | A cherry blossom tree that grows itself under a full moon, with drifting petals, fireflies and a mirror lake. | Move the cursor to swirl the petals; click to grow a new tree |
| `study-session.html` | A cozy late-night coding scene with a coder in headphones, scrolling code and a starry window. | Click to pause |
| `rainy-study.html` | A detailed anime-style student writing at his desk on a rainy night, with rain sliding down the glass and city bokeh outside. | Click to pause |
| `quotes.html` | **Daily Fuel**: a motivational quote widget with anime, code, nature and mindset quotes. It opens on a quote of the day. | Click, press Space or use **Next** for a new quote; filter by category, auto-rotate, copy |

## How to use

### Open locally
Open any `.html` file in a browser.

### Embed in Notion
1. In this repo, go to **Settings → Pages** and deploy from the `main` branch (root).
2. Each widget is then served at a URL like:
   ```
   https://senorking.github.io/Notion-widget/<file>.html
   ```
3. In Notion, type `/embed`, paste the URL, and drag the block to size it.

Suggested embed heights:
- Scenes (`night-drive`, `sakura-lake`, `study-session`, `rainy-study`): about 300–500px
- `quotes.html`: about 260–360px

### Customize
Colors, text, quotes and animation timing all live directly in each file. For example, add your own quotes to the `QUOTES` list in `quotes.html`.

## Notes

- This project is intentionally lightweight and portable.
- Every widget respects the browser's reduced-motion setting.
- `quotes.html` stores your category filter and auto-rotate setting in your browser only, so they don't sync between devices.
- The visuals are AI-generated and are meant to serve as creative mood pieces rather than production-ready apps.
