# Personal Website — Quarto + GitHub Pages

## Files included
```
├── _quarto.yml        # Site config (navbar, theme, output dir)
├── index.qmd          # Home page (profile card)
├── publications.qmd   # Publications page
├── styles.css         # Custom styling
└── images/
    └── profile.jpg    ← PUT YOUR PHOTO HERE
```

## Quick start

### 1. Add your photo
Place your photo at `images/profile.jpg` (portrait rectangle recommended, e.g. 400×530 px).

### 2. Edit your info
Open `index.qmd` and update:
- Your name, position, institution
- Summary paragraph
- Research interest tags
- Social links (LinkedIn, Google Scholar, GitHub URLs)

Open `publications.qmd` and replace the placeholder entries with your real papers.

### 3. Render the site
```bash
quarto render
```
This generates the site into the `docs/` folder.

### 4. Push to GitHub Pages
1. Push everything (including `docs/`) to your GitHub repo.
2. Go to **Settings → Pages**.
3. Set source to **Deploy from branch → main → /docs**.
4. Your site will be live at `https://yourusername.github.io/reponame/`.

## Tips
- To add a new tab (e.g., CV, Teaching), create a new `.qmd` file and add it to `_quarto.yml` under `website > navbar > left`.
- Colours can be changed in `styles.css` — edit the `:root` CSS variables at the top.
