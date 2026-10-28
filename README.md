# THE PUMP FILES

An independent website documenting Alon Cohen's Pump.fun business history and the public company tree.

**Website:** https://pumpfun.fyi  
**Hosted fallback:** https://the-pump-files.element4200.chatgpt.site

## Contents

- Public company and product tree with 17 clickable entries.
- Eight dated history milestones from 2023 to 2026.
- Real brand logos and links to supporting public sources.
- A configurable community-token purchase link.

## Run locally

Serve this directory with any static HTTP server. No installation or build step is required. For example, with Python installed:

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Configure the token

Edit `config.js` to set the actual Solana mint address and its matching Pump.fun coin URL. Buy buttons show launch pending until both match. This site does not launch tokens, connect wallets, collect keys, or execute transactions.

## Hosting and source

This repository is the public source copy of the website. The production site is hosted by Sites; the custom domain is managed through Cloudflare DNS. GitHub commits do not automatically deploy to production.

## Sources and trademarks

Company information links to public filings, official terms, and dated reporting. Logo and portrait provenance is recorded in `assets/sources.json`. Logos and images belong to their respective owners and identify the businesses discussed.

This is an independent community project, without affiliation or endorsement from Alon Cohen, Pump.fun, or the featured businesses. The community token owns none of these companies and grants no equity or revenue rights.
