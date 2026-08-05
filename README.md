# Roshith E — Portfolio

Interactive single-page portfolio built with vanilla HTML, CSS, and JavaScript.
No build step. No frameworks. Deploy anywhere in seconds.

## Deploy to GitHub Pages (recommended)

1. Create a new repo named **`RoshithE.github.io`** on GitHub
2. Push this folder to that repo:

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/RoshithE/RoshithE.github.io.git
git branch -M main
git push -u origin main
```

3. Go to repo Settings → Pages → Source: `main` branch → Save
4. Live at: **https://RoshithE.github.io**

## Customise before pushing

Open `index.html` and update these placeholders:

| Line | What to change |
|------|---------------|
| `roshith@example.com` (×3) | Real email address |
| LinkedIn URL | Real LinkedIn profile URL |
| `About` section text | Edit to match actual background |
| Stat cards (6+, 96, 3, 8%) | Update if numbers change |
| `UK Accidents` GitHub link | Replace `#` with real repo URL |

## Features

- Typing animation hero (cycles through 4 roles)
- Scroll progress bar
- Intersection Observer fade-in on scroll
- Project filter buttons (All / AI / ML / Stats / Data Engineering)
- Active nav highlight on scroll
- Mobile-responsive with hamburger menu
- Sticky blur navbar
- Side email + social links (desktop)
- Zero dependencies — no npm, no build, no framework
