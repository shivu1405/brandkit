# Brand Kit Generator 🎨

**AI-powered design system generator. Production-ready brand kits in seconds.**

Enter your brand details and get a complete design system — color palette, semantic tokens, typography scale, spacing grid, and a Figma-ready export. No designer needed.

🔗 **[Live Demo](https://shivu1405.github.io/brandkit/)**

---

## what it does

- **Color Palette** — generates a full palette from your primary brand color, including semantic tokens (primary, secondary, accent, surface, text)
- **Typography Scale** — font pairings and a complete type scale matched to your brand personality
- **Spacing Grid** — 8pt grid system ready to drop into any project
- **Token Export** — download your design tokens in CSS Custom Properties, JSON (Style Dictionary compatible), or SCSS Variables
- **Figma-ready** — exports a `.zip` with everything you need to set up a Figma library

---

## inputs

| Field | Options |
|-------|---------|
| Brand name & industry | 10 industry presets |
| Primary brand color | Color picker |
| Visual style | Minimal / Bold / Classic / Playful / Luxury / Technical |
| Brand personality | Mix of 2–3 traits |
| Target audience | Free text |
| Token format | CSS / JSON / SCSS |

---

## tech stack

- HTML / CSS / JavaScript (single-file, fully client-side)
- Anthropic Claude API for design system generation
- Zero backend, zero dependencies

---

## how to run locally

```bash
git clone https://github.com/shivu1405/brandkit.git
cd brandkit
# open index.html in your browser — no build step needed
```

You'll need a Claude API key from [console.anthropic.com](https://console.anthropic.com/) to generate kits.

---

## why I built this

Early-stage founders waste time stitching together colors and fonts from scratch, or pay for tools that are overkill for an MVP. This gives you a coherent, exportable design system in under a minute — so you can focus on building the actual product.
