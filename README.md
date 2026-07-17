# The Long Game

A free, plain-English guide to U.S. retirement and tax-advantaged accounts, for tax year 2026.

## Pages

- **`index.html`** — the landing page. Explains the whole idea in one table and routes to the two halves.
- **`guide.html`** — the field guide. The mental model, every account, 2026 limits, the funding waterfall, strategy by income and age, and a step-by-step Fidelity mega-backdoor Roth walkthrough.
- **`the-long-game.html`** — four interactive career stories (physician, engineer, teacher, founder) with sliders that re-run a 40-year simulation live.
- **`404.html`** — styled not-found page, served automatically by GitHub Pages.

All static HTML. No build step, no dependencies, no server, no tracking. Open any file in a browser and it works.

## Hosting on GitHub Pages (free)

1. Create a new **public** repository.
2. Upload these files to the root of the `main` branch.
3. **Settings → Pages → Build and deployment → Source → Deploy from a branch**.
4. Branch **`main`**, folder **`/ (root)`**. Save.
5. Live in about a minute at `https://<username>.github.io/<repo>/`

No GitHub Actions workflow needed — there's nothing to build.

### Notes

- `.nojekyll` tells Pages to serve files as-is rather than running Jekyll. Optional here, but avoids surprises.
- Pages sites are **always public**, even from a private repo.
- Free tier: 1 GB site, 100 GB/month bandwidth. This site is ~180 KB.
- Custom domains are free, with automatic HTTPS.

## Disclaimer

Educational material, not financial or tax advice. Figures are for tax year 2026, verified against IRS sources (Rev. Proc. 2025-32, Notice 2025-67, Pub 590-A) in July 2026. Limits change annually — verify current numbers before acting.
