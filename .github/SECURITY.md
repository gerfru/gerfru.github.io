# Security Policy

## Scope

This is a static website with no server-side code, databases, or user authentication. The attack surface is limited to the HTML, CSS, and client-side JavaScript served via GitHub Pages.

## Security-Scanning im SDLC

| Schicht | Tool | Trigger |
|---------|------|---------|
| Secret-Scan | gitleaks | CI |

## Sicherheitslücken melden

Schwachstellen bitte **nicht** als öffentliches GitHub Issue melden.
Stattdessen: GitHub → Security → "Report a vulnerability" (Private Disclosure) oder direkt:

- Email: gerald@frhmnn.eu
- Subject: `[SECURITY] gerfru.github.io`

Meldungen werden innerhalb von 48 Stunden bestätigt.

## Out of scope

- Vulnerabilities in GitHub Pages infrastructure (report to GitHub directly)
- Social engineering attacks
- Issues requiring physical access
