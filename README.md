# Raza Mehdi — Personal Site

Clean, minimalist academic portfolio with an elegant light/dark theme toggle and smooth scroll navigation.

**Live:** https://razamehdi1214.github.io/cv-site-aurora-ember/

Single-file static site (`index.html`), served via GitHub Pages.

## Design

- Serif/sans typography pairing (Newsreader + Inter, JetBrains Mono for metadata)
- Restrained single-accent (ember/sienna) palette with full light & dark themes; the name and email share one ink color
- Theme toggle persists to `localStorage` and respects system preference
- Click-to-switch panel navigation — About is the landing; Research, Publications, Talks, Teaching, and Contact each open as their own panel (no infinite scroll)
- Sub-tab filters for dense publication, talk, and service lists
- Fully responsive with a mobile menu

## Local preview

```bash
python3 -m http.server 8080
# open http://127.0.0.1:8080
```
