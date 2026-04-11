# CyberDict

**CyberDict** is a single-file, static cybersecurity learning dictionary — no build step, no dependencies, no frameworks. Just open `index.html` and start learning.

🔗 **Live site:** https://xim-mix-x-im.github.io/cyberdict

## Features

- 43 cybersecurity terms across six categories: **Attack, Defense, Concept, Tool, Protocol, Standard**
- Instant full-text search — searches term names, definitions, and "see also" tags
- Filterable by category via pill buttons
- Expandable detail cards with examples, prevention tips, and cross-references
- Dark theme, fully responsive, keyboard accessible (Enter/Space to expand)
- Zero external dependencies — everything is self-contained in `index.html`

## Usage

Open `index.html` directly in any modern browser, or serve via any static host (GitHub Pages, Netlify, Vercel, etc.).

```bash
# local preview with Python
python -m http.server 8080
```

Then navigate to `http://localhost:8080`.

## Deployment (GitHub Pages)

1. Push `index.html` to the `main` branch of your repository.
2. Go to **Settings → Pages → Source → Deploy from branch → main / (root)**.
3. GitHub Pages will serve your site at `https://<username>.github.io/<repo>`.

## Contributing

Contributions of new terms, improved definitions, or UI enhancements are welcome. Please open an issue or PR.

## License

MIT
