# Marketing-site architecture

`apostille-me.github.io` is the public Astro marketing, documentation, privacy, support, and service-status surface for Apostille.me. The existing responsive site and its production build, test, SEO, and GitHub Pages configuration are canonical and must be evolved in place rather than replaced by a bootstrap placeholder.

## Fleet relationships

- `apostille-me-libs` owns reusable apostille domain, document-status, provider, and API behavior.
- `apostille-me-clients` exposes typed workflow, upload, status, and error clients.
- `apostille-me-infra` owns Kubernetes, observability, deployment, and bounded edge behavior.
- `apostille-me.github.io` owns public product narrative and documentation.
- `apostille-me-monorepo` coordinates pinned revisions and cross-repository integration checks.

The marketing site may link to versioned public contracts but must not duplicate service logic or become a generic edge proxy. Public copy, accessibility, performance, and stable URLs are product behavior and require review and tests.
# Architecture

Marketing, documentation, privacy, support, and public service-status content for Apostille.me.

## Fleet

- `apostille-me-libs`
- `apostille-me-clients`
- `apostille-me-infra`
- `apostille-me.github.io`
- `apostille-me-monorepo`

Interfaces own wire formats; libraries own reusable domain behavior; clients consume versioned contracts; runtimes own deployment behavior; monorepos coordinate pinned revisions. Edge code is allowlisted and never a generic proxy.
