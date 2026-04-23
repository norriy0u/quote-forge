# 🔥 Quote Forge — Smelt Words Into Wisdom
**VishwaNova 2026 · National Level Weboreel AI Hackathon**

> Throw in a vibe. Get back a quote that feels like it was written just for you. A procedural quote engine wrapped in a blacksmith's forge aesthetic.

## ✨ Features
- ⚒️ **Forge Animation UI:** The hero section features a CSS-drawn blacksmith forge with animated ember particles rising from the base using Canvas, and a hammer that strikes on quote generation via a `rotate` keyframe swing.
- 🎰 **Template Engine:** 50+ quote skeleton templates with bracketed slots (`[emotion]`, `[element]`, `[verb]`) are filled procedurally from curated word banks — producing thousands of unique, grammatically coherent quotes.
- 🎨 **Mood Theming:** Select a mood tag (Stoic, Chaotic, Poetic, Savage, Zen) before forging. The word banks, fonts, and color palette all shift to match — Stoic uses serif fonts and muted grays; Chaotic goes full neon monospace.
- 🖼️ **Canvas Quote Card Export:** The generated quote is rendered onto an HTML5 Canvas with a stylized background, chosen font, and decorative border — downloadable as a PNG in one click.
- 📣 **Crowd Approval:** A CSS crowd-o-meter fills up as you click "This hits different" — at 100%, a confetti burst drops from the top of the viewport.

## 🛠️ Tech Stack
- **HTML5** — Canvas API for quote card rendering + PNG export via `toDataURL`.
- **Vanilla CSS3** — Forge UI illustration, ember particle keyframes, mood-based CSS variable theming.
- **Vanilla JavaScript** — Template slot-fill engine, word bank arrays, mood-to-style mapper.

## 📸 Try It Out
Double-click `index.html` in any modern browser. Fully offline.

---
Built with ❤️ for VishwaNova 2026
