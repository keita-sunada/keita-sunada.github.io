# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Static personal academic website for Keita Sunada, hosted via GitHub Pages at `keita-sunada.github.io`. No build system, framework, or package manager — just plain HTML/CSS served directly by GitHub Pages.

## Structure

- `index.html` — Main page (research, CV link, bio)
- `style.css` — Single stylesheet for all pages
- `japanese.html`, `links.html` — Secondary pages (currently commented out in nav)
- `archived/` — Previous versions of the site
- `uploads/` — PDFs of papers and appendices
- `cv_Keita_Sunada.pdf`, `main01.pdf` — CV and job market paper PDF
- `CV.bib` — BibTeX file for publications

## Deployment

Pushing to `main` automatically deploys via GitHub Pages. There is no build step.

## Conventions

- CSS comments are in Japanese (e.g., layout positioning notes)
- Link color is purple (`#8a0087`)
- Research papers are listed in reverse chronological order using `<ol reversed>`
