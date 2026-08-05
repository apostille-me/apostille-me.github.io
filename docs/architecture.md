# Architecture

Marketing, documentation, privacy, support, and public service-status content for Apostille.me.

## Fleet

- `apostille-me-libs`
- `apostille-me-clients`
- `apostille-me-infra`
- `apostille-me.github.io`
- `apostille-me-monorepo`

Interfaces own wire formats; libraries own reusable domain behavior; clients consume versioned contracts; runtimes own deployment behavior; monorepos coordinate pinned revisions. Edge code is allowlisted and never a generic proxy.
