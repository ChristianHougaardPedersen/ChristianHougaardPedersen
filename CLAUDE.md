# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a [GitHub profile repository](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) (`ChristianHougaardPedersen/ChristianHougaardPedersen`). Its sole file, `README.md`, is rendered as the public-facing profile page at github.com/ChristianHougaardPedersen. There are no builds, tests, or deployable artifacts.

## README Structure

The `README.md` is written in HTML (not Markdown) and is organized into sections, each rendered as a centered row of icon badges:

- **Languages** — C, C#, Java, JavaScript
- **Front-end** — Bootstrap, CSS3, HTML5, React, Tailwind CSS
- **Back-end** — Node.js, Spring
- **Tools** — Bash, Docker, Git, Ubuntu, PostgreSQL, SQLite, RabbitMQ, .NET
- **Programs** — IntelliJ IDEA, DataGrip, Rider, VS Code

## Icon Sourcing Convention

Badge icons are `<img>` tags pulled from three CDNs:

- `raw.githubusercontent.com/devicons/devicon/master/icons/` — most language/framework icons
- `www.vectorlogo.zone/logos/` — tools where devicons lacks an SVG (Bash, Git, Spring, RabbitMQ, SQLite, Tailwind)
- `resources.jetbrains.com/storage/products/company/brand/logos/` — JetBrains IDE icons
- `upload.wikimedia.org` — fallback for icons not available elsewhere (IntelliJ IDEA)
- `github.com/devicons/devicon/blob/master/` — used for a few icons that aren't on the `raw.githubusercontent.com` CDN path (Ubuntu, VS Code)

When adding a new technology icon, prefer the devicons CDN first, fall back to vectorlogo.zone, then Wikimedia.

## Editing Guidelines

- All sections use `<h3 align="center">` for headings and `<p align="center">` wrapping `<a><img></a>` icon links.
- Icon `<img>` tags use `width="40" height="40"` uniformly.
- Keep `target="_blank" rel="noreferrer"` on all external `<a>` tags.
- Contact info and social links live at the top of the file, above the `***` divider.
