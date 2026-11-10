# Khaos — Personal Portfolio

A cinematic, electric-blue personal developer portfolio.

## Features
- Responsive single-page design
- Animated intro, scroll reveals, cursor glow, and particle network
- Live public profile and repository data from the GitHub REST API
- Reduced-motion accessibility support
- GitHub Pages deployment via GitHub Actions

## Local preview
Open `index.html` in a browser, or run a local static server:

```bash
python3 -m http.server 4173
```

Then visit http://localhost:4173.

## Deployment
Push the `main` branch. The workflow in `.github/workflows/pages.yml` deploys the site to GitHub Pages.
