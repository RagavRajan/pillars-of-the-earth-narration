# Pillars of the Earth — A Narrator's Companion

A six-evening spoken-narration companion to Ken Follett's *The Pillars of the Earth* (1989), plus a historical-context primer covering the Anarchy, Becket's murder, feudal hierarchies, Gothic architecture, and the medieval wool economy.

The site does **not** reproduce the novel. It is a derivative storytelling guide.

## Stack

- [Quarto](https://quarto.org) website
- Hosted on GitHub Pages

## Local preview

```bash
quarto preview
```

## Build

```bash
quarto render
```

## Deploy to GitHub Pages

One-time setup (after pushing the repo to GitHub):

```bash
quarto publish gh-pages
```

This creates a `gh-pages` branch, pushes the rendered site, and configures GitHub Pages.

## Files

| File | Role |
|---|---|
| `_quarto.yml` | Site config (theme, nav, render list) |
| `index.qmd` | Landing page |
| `Context.md` | Historical-context primer |
| `Day 1 - The Hanging and the Snow.md` | First narration session (Part I) |
| `styles.css` | Reading-first typography |

## What's NOT in the repo

The raw text of the novel (`pillars of the earth.md`, `pillars of the earth.pdf`) is `.gitignore`d. It is copyrighted material and cannot be redistributed.

## Licence

Original narration and context writing in this repo: CC BY-NC-SA 4.0 (attribution, non-commercial, share-alike).
The underlying novel is © Ken Follett, 1989 — referenced under fair use for criticism and commentary.
