# PNFL Team Comparison Tool

A fully client-side NFL team comparison tool built for the PNFL fantasy/simulation league.

**Live site:** https://YOUR-USERNAME.github.io/pnfl-comparison

---

## Features

- Compare 2–4 teams side-by-side across all position groups
- **Offensive Line** broken into Center (C), Guard (G), Tackle (T)
- **Defensive Line** broken into Defensive End (DE), Defensive Tackle (DT)
- Full Secondary breakdown: CB (depth 5) and S (depth 4)
- Configurable attribute weights per position (SP, AC, AG, ST, HA, EN, IN, DI)
- Configurable roster depth per position group
- ESPN transparent team logos
- SVG football icons throughout
- Radar chart visualization (attribute view + unit view)
- Animated winner banner
- Created by S.Hamilton

---

## How to Update

### Quick edit workflow
1. Edit `index.html` locally (or directly on GitHub)
2. Commit and push — the live site updates within ~60 seconds

### Full local dev workflow
```bash
# Clone your repo
git clone https://github.com/YOUR-USERNAME/pnfl-comparison.git
cd pnfl-comparison

# Make your changes to index.html
# Then push:
git add index.html
git commit -m "describe your change"
git push origin main
```

The site runs entirely from `index.html` — no build step, no dependencies to install.

---

## Deploying Updates from Claude

When Claude gives you an updated `PNFL_Team_Comparison.html`:
1. Download it
2. Rename it to `index.html`
3. Replace the file in your local repo folder
4. Run:
```bash
git add index.html
git commit -m "update: [describe what changed]"
git push origin main
```

---

## Repo Structure

```
pnfl-comparison/
├── index.html        ← The entire app (single file)
└── README.md         ← This file
```

---

*Created by S.Hamilton*
