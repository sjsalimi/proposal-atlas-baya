# ATLAS × BAYA — Interactive Investment Proposal

This repository contains the Persian (RTL) HTML investment proposal for Atlas Agent Innovator and BAYA.

## Main entry
- `index.html` — standalone site (inline layout, scripts, artwork)

## Deploy with Cloudflare Pages (Git integration)
1. Cloudflare Dashboard → **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
2. Authorize GitHub and select private repository `sjsalimi/proposal-atlas-baya`.
3. Choose branch `main`.
4. Framework preset: `None` (no framework).
5. Build command: `mkdir -p dist && cp index.html dist/index.html`
6. Build output directory: `dist`; root directory: repository root.
7. Deploy and check the generated `*.pages.dev` hostname.

## Confidentiality — important
The GitHub repository is **private** but the deployed Cloudflare Pages website is **public by default**. Before sharing the URL, use **Cloudflare Access** to limit access to approved email addresses (for example, representatives of BAYA). Protect both the production `project.pages.dev` URL and preview deployment URLs. Merely enabling the Pages preview access policy does **not** secure production; consult the Cloudflare Pages Known issues guide under "Enable Access on your *.pages.dev domain".

Documentation:
- https://developers.cloudflare.com/pages/get-started/git-integration/
- https://developers.cloudflare.com/pages/platform/known-issues/
- https://developers.cloudflare.com/cloudflare-one/integrations/identity-providers/one-time-pin/

## Updates
Future pushes to `main` trigger an automatic Pages deployment after the Git integration is configured.

© 2026 R&T Department — Atlas Agent Innovator. Confidential BAYA proposal.
