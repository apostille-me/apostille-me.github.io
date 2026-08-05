# apostille-me.github.io

Astro marketing site for **Apostille Me**.

- Built with Astro, not Jekyll.
- Uses GitHub Pages Actions deployment.
- Includes a responsive landing page, SEO metadata, favicon, proof points, workflow, integrations, architecture, and launch CTA.
- `public/.nojekyll` is present only to bypass Jekyll processing on Pages; there is no Jekyll site or `_config.yml`.

## Commands

```bash
npm install
npm run dev
npm run build
npm test
```

## Repository family

The site links the public product narrative to the `apme-clients`, `apme-libs`, `apme-monorepo`, and `apme-infra` repositories. GitHub Pages deployment is handled by Actions; Jekyll is not used.
