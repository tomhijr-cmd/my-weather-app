# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## What's Here

A weather app built with vanilla JavaScript, HTML, and CSS — no frameworks, no dependencies.

- **`index.html`** — Single-file app (HTML + CSS + JS all in one file)

## Running the App

Open `index.html` directly in a browser — no build step required.

## Architecture Guidelines

- **Single file**: All HTML, CSS, and JavaScript lives in `index.html`
- **No frameworks**: Vanilla JS only — no React, Vue, jQuery, etc.
- **No build tools**: No npm, webpack, or bundlers
- **Persistence**: Use `localStorage` for any data that should survive page reloads
- **UI**: Clean, modern UI — readable typography, good spacing, thoughtful color choices
- **Code style**: Simple and readable over clever — prefer clear variable names and straightforward logic
