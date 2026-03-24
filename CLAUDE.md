# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Static personal website for Daniel Eckermann. No build system, no dependencies, no framework.

## Architecture

- **`index.html`** — The entire site: markup, inline `<style>`, and content. There is no JavaScript.
- **Static assets** — Images (`portrait.webp`, `collectjs.webp`, `utleiekalkulator.webp`, `favicon.png`) served alongside `index.html`.
- **`app-ads.txt`** — Ad network verification file.

## Development

Open `index.html` directly in a browser. No build step, no dev server required.

## Key conventions

- All CSS is inline in `<style>` within `index.html` — do not extract to a separate file.
- Dark theme (`#0f1219` background) with consistent color palette defined in the existing styles.
- Responsive breakpoint at 600px using a single `@media` query.
