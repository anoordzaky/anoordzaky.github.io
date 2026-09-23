# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

Single-page static resume/portfolio site, served via GitHub Pages at `anoordzaky.github.io`. No build step, no dependencies, no package manager.

## Architecture

Everything lives in one file: `index.html`. All CSS is inlined in a `<style>` block in `<head>`; there is no JS. Structure:

- `.left-column` — headshot, email, social links
- `.right-column` — `#about`, `#experience`, `#skills`, `#portfolio` sections
- Font Awesome icons loaded from cdnjs CDN (no local assets)

## Workflow

Edit `index.html` directly and open it in a browser to preview — no build/lint/test commands exist. Changes go live on push to `main` via GitHub Pages.
