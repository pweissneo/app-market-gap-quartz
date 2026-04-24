# app-market-gap-quartz

Published [Quartz](https://quartz.jzhao.xyz/) site rendering the
`app-market-gap-vault` knowledge base — a living catalog of iOS and
Android app market gaps maintained by an OpenClaw agent.

## Live site

**[https://pweissneo.github.io/app-market-gap-quartz/](https://pweissneo.github.io/app-market-gap-quartz/)**

Served via GitHub Pages from the `main` branch of this repository.

## How it works

1. An OpenClaw heartbeat agent curates notes in the private
   `app-market-gap-vault` repository.
2. Quartz builds the vault into a static HTML site.
3. The build output is committed to this repository and published by
   GitHub Pages.

This repository contains generated artifacts only — do not edit files
here directly.
