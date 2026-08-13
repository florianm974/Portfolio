# Portfolio — Florian Marianne

Portfolio personnel présentant mon profil, ma stack, ma formation et mes projets.

**Live →** [florianm974.github.io/portfolio](https://florianm974.github.io/portfolio/)

---

## Présentation

> Single page dark-theme, tons or/violet. Pas de framework, pas de build.

---

## Stack

- **HTML / CSS / JS** — vanilla, tout inline dans `index.html`
- **manifest.json** — PWA light (icônes, thème)
- **404.html** — page 404 GitHub Pages
- Hébergé sur **GitHub Pages**

---

## Structure

```
portfolio/
├── index.html                 # Portfolio complet (HTML, CSS, JS inlinés)
├── 404.html                   # Page 404 personnalisée
├── manifest.json              # Manifest PWA
├── cv/                        # Source LaTeX du CV — main.tex
├── cv-marianne-florian.pdf    # CV compilé en local, committé avec la source
└── LICENSE
```

---

## Fonctionnalités

- Dark theme responsive
- Animations au scroll
- Navigation avec scroll spy et menu mobile
- Section projets avec liens site + GitHub
- CV disponible en téléchargement direct
- CV en LaTeX (`cv/main.tex`), compilé localement via LaTeX Workshop (VS Code/VSCodium) puis committé
- Accessibilité (ARIA, prefers-reduced-motion)

---

## Licence

MIT — voir [LICENSE](LICENSE)
