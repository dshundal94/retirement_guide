# The Long Game

A two-page guide to U.S. retirement and tax-advantaged accounts, for tax year 2026.

- **`index.html`** — the field guide. The mental model, every account, 2026 limits, the funding waterfall, strategy by income and age, and a step-by-step Fidelity mega-backdoor Roth walkthrough.
- **`the-long-game.html`** — four interactive career stories (physician, engineer, teacher, founder) with sliders that re-run a 40-year simulation live.

Both are self-contained static HTML. No build step, no dependencies, no server. Open either file directly in a browser and it works.

## Hosting it on GitHub Pages (free)

1. Create a new **public** repository on GitHub.
2. Upload these files to the root of the `main` branch.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set branch to **`main`** and folder to **`/ (root)`**. Click **Save**.
6. Wait ~1 minute. Your site is live at `https://<your-username>.github.io/<repo-name>/`

No GitHub Actions workflow is needed — there is nothing to build.

### Notes

- `.nojekyll` tells Pages to serve the files as-is instead of running them through Jekyll. Optional here, but it avoids surprises and speeds up deploys.
- Pages sites are **always public**, even if the repository is private.
- Free tier: 1 GB site size, 100 GB/month bandwidth. This site is ~170 KB.
- Custom domains are supported for free, with automatic HTTPS.

## Disclaimer

Educational material, not financial or tax advice. Figures are for tax year 2026 and change annually. Verify current limits before acting, and take real decisions to a fee-only fiduciary advisor and a CPA.
