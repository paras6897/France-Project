# Security policy

## Scope

This is a static GitHub Pages project. It does not collect passwords, payment data, API keys, or other sensitive credentials.

## Reporting a vulnerability

If you discover a security issue in this project, please avoid posting exploit details publicly. Use GitHub's private vulnerability reporting feature for the repository when available.

For ordinary website bugs or design issues, open a normal GitHub issue.

## Security practices

- GitHub Actions are pinned to immutable commit SHAs.
- The Pages workflow uses least-privilege permissions.
- Dependabot monitors GitHub Actions dependencies.
- The site uses HTTPS on GitHub Pages and a restrictive browser Content Security Policy.
- No secrets are embedded in the website source.
