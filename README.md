# REMagic

**Live Site**
Temporary: [https://remarkable-swan-bd8b87.netlify.app](https://remarkable-swan-bd8b87.netlify.app)
Custom domain coming soon.

## Project Overview

REMagic is the marketing website for professional magician **Robert Ellams**. The goal is a fast, accessible, single‑page experience showcasing services, testimonials, and a gallery, with a clear call‑to‑action for booking enquiries.

## Local Development

Because the site is currently plain HTML/CSS/JS:

```bash
git clone https://github.com/Ready2Learn2025/REMagic.git
cd REMagic
open index.html   # or double‑click the file
```

When you introduce build tooling (Vite, Astro, etc.), update these instructions accordingly.

## Deployment (Netlify)

Netlify is linked to the `main` branch.

* **Build command:** *empty* (static)
* **Publish directory:** `/` (repo root)

Every push to `main` triggers an automatic redeploy and purge of the CDN cache.

## Tech Stack

* **HTML5** – semantic markup
* **CSS3** – custom styles (currently in `/css/styles.css`)
* **JavaScript (vanilla)** – minimal animations (optional)

No frameworks yet; keeping it lightweight.

## Contributing

1. **Fork** the repo, then clone your fork locally.
2. Create a feature branch: `git checkout -b feat/your-feature`.
3. Commit with [Conventional Commits](https://www.conventionalcommits.org/) style.
4. Open a **Pull Request** back to `main`.
5. A Netlify preview build will appear automatically.

## Roadmap

* [ ] Improve mobile responsiveness (hero text scaling, gallery grid)
* [ ] Add a lightbox to the Gallery
* [ ] Integrate Netlify Forms for the contact form
* [ ] Add basic unit tests once JS grows
* [ ] Set up GitHub Actions CI (HTMLHint, Lighthouse CI)

## License

[MIT](LICENSE)

---

© 2025 Robert Ellams
