# NxCode — Website

Official landing page for **NxCode (`nxc`)** — the AI coding agent that lives in your terminal.

Live site: **https://nxcodeobject.github.io/coding/**

This repository contains the public marketing site for NxCode: a static, bilingual (Indonesian/English) page that introduces the agent, its features, supported model providers, installation steps, and the main CLI commands.

## What the site covers

- **Hero & install box** — copy-paste install commands for Windows (PowerShell) and Linux/macOS
- **Features** — Build & Plan agents, bring-your-own-API-key models, web UI/server, MCP extensions, LSP awareness, sessions & snapshots
- **Providers** — Anthropic, OpenAI, Google, Azure, Bedrock, Groq, Mistral, xAI, and many more
- **Install steps** — 3-step quick start
- **CLI reference** — the most-used `nxc` commands

## Tech

Plain **HTML + CSS + JavaScript**. No framework, no build step, no dependencies to install. English/Indonesian strings are handled by a small i18n dictionary inside the page; the choice is stored in `localStorage`.

## Running locally

Open `index.html` directly, or serve the folder with any static server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

> The page pulls Google Fonts from a CDN, so an internet connection is needed for full styling.

## Project structure

```
index.html   Page markup + i18n dictionary
style.css    Theme and layout
logo.png     Brand logo
```

## Related

- **NxCode (`nxc`)** — source & releases: https://github.com/nxcodeobject/code
- **NXC Desktop SDK** — https://github.com/nxcodeobject/nxc
- **NXDOM** — the organization behind these projects: https://iyanrsaleh.github.io/nxdom/

## Sponsor

NxCode is developed in the open and free to use. If you or your organization would like to support the work, see [GitHub Sponsors](https://github.com/sponsors/iyanrsaleh).

## License

Released under the [MIT License](LICENSE).
