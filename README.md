<div align="center">

# ✦ Anshul Pagar — Portfolio

**A space-themed portfolio with a celestial koi that follows your scroll.**

Vanilla HTML · CSS · JavaScript — one file, no framework, no build step.

[**Live Site**](https://anshulpagar7.github.io/portfolio/) · [LinkedIn](https://linkedin.com/in/anshulpagar) · [Email](mailto:anshulpagar@gmail.com)

</div>

---

## 🐟 The Signature

A glowing **celestial koi** — segmented body, flapping fins, forked tail, spark trail — swims across the entire site on a canvas layer:

- **Scroll down** → it dives. **Scroll up** → it rises. Scroll fast → it swims harder.
- **Click empty space** → drops a food pellet; the koi swims over and eats it in a burst of sparks.
- **KOI FRENZY** (hidden in the command palette) → 12 seconds of double-speed chaos.

## ⚡ Features

| | |
|---|---|
| ⌘K **Command palette** | Linear-style navigation — jump anywhere, copy email, secret commands |
| 🌌 **Living background** | Twinkling starfield, shooting stars, section-based nebula tints |
| ✍️ **Scroll choreography** | GSAP + ScrollTrigger: char-split headings, word-fill paragraphs, velocity skew, kinetic marquee, ghost-number parallax |
| 📂 **Expandable projects** | 9 projects open into full detail modals — architecture, metrics, links |
| 🏅 **Certificate gallery** | 17 certificates as live image tiles with an on-site A4 lightbox (‹ › navigation) |
| 📄 **Resume viewer** | In-page A4 portrait viewer + PDF download |
| 🧲 **Tactile UI** | Custom cursor, magnetic buttons, 3D-tilt cards, glitch-decode labels |
| 🥚 **Easter eggs** | Feed the koi, KOI FRENZY, and a console message for the devtools-curious |

## 🛠 Under the Hood

- **Zero dependencies at build time** — GSAP + ScrollTrigger via CDN, everything else hand-rolled
- **Two canvas layers** — starfield/shooting-stars + the koi engine (segment-chain physics)
- **Data-driven content** — projects, experience, certifications, and achievements live in plain JS arrays at the top of the file (marked `✏️ EDIT ZONE`); the site renders them automatically
- **Accessible** — keyboard-navigable cards and modals, focus styles, `prefers-reduced-motion` respected throughout
- **Single `index.html`** — deploys on GitHub Pages, Vercel, or Netlify as-is

## 🚀 Run It

```bash
# there is no step 2
open index.html
```

## ✏️ Updating Content

Open `index.html`, find the `✏️ EDIT ZONE` banner in the `<script>`, and add entries to `PROJECTS`, `EXPERIENCE`, `CERTIFICATIONS`, `ACHIEVEMENTS`, or `LEADERSHIP`. No other code changes needed.

---

<div align="center">

**Anshul Pagar** · B.Tech CSE @ SRM IST KTR · Nashik → the stars

*Press `Ctrl+K` on the site. Try "KOI FRENZY".*

</div>
