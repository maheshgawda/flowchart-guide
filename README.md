# Flowchart — A Field Guide

A single-page visual reference to flowcharts: symbols, history, and standards — built with plain HTML/CSS, no build step, no dependencies.

**Live site:** https://maheshgawda.github.io/flowchart-guide/

## What's on the page

- The ANSI/ISO 5807 symbol legend (terminal, process, decision, input/output, connectors, and more)
- A sample decision-loop diagram
- A short history, from Gilbreth's 1921 flow process chart to ISO 5807 (1985)
- The four flowchart types (Sterneckert, 2003)
- Notes on parallel/fork-join notation and where flowcharts fall short (e.g. recursion)

## Running it locally

No build tools needed — just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server
```

## Deployment

This repo is deployed with **GitHub Pages**, serving `index.html` directly from the `main` branch root. Any push to `main` updates the live site automatically.

## Source

Content adapted from Wikipedia's [Flowchart](https://en.wikipedia.org/wiki/Flowchart) article, available under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
