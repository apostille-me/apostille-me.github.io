# apostille-me.github.io

Astro marketing site for **Apostille Me**.

- Built with Astro, not Jekyll.
- The canonical document is `src/pages/index.astro`; only the tested `dist/` artifact is published.
- Uses GitHub Pages Actions deployment.
- Includes a responsive landing page, SEO metadata, favicon, proof points, workflow, integrations, architecture, and launch CTA.
- `public/.nojekyll` is present only to bypass Jekyll processing on Pages; there is no Jekyll site or `_config.yml`.

## Commands

```bash
npm ci --ignore-scripts
npm run dev
npm run build
npm test
```

## Repository family

The site links the public product narrative to the `apme-clients`, `apme-libs`, `apme-monorepo`, and `apme-infra` repositories. GitHub Pages deployment is handled by Actions; Jekyll is not used.
Marketing, documentation, privacy, support, and public service-status content for Apostille.me.

Initialized through `DEN-1951` as a testable `marketing` foundation. Product behavior continues through focused pull requests.

```bash
python3 scripts/verify_repo.py
```
