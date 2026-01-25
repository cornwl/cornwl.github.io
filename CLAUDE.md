# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an academic personal website built with Jekyll using the Academicpages theme (forked from Minimal Mistakes). It's deployed via GitHub Pages at https://cornwl.github.io.

## Common Commands

```bash
# Install dependencies
bundle install

# Run local development server with live reload
bundle exec jekyll liveserve

# Run with development config (disables analytics, expanded CSS)
bundle exec jekyll serve --config _config.yml,_config.dev.yml

# Build JavaScript (if modifying JS)
npm run build:js
```

The site auto-deploys to GitHub Pages when pushing to master branch.

## Architecture

**Collections** (content types with their own pages):
- `_teaching/` - Course pages. Active courses at root, archived in `_archive/` subdirectory
- `_publications/` - Academic papers
- `_talks/` - Presentations and seminars
- `_portfolio/` - Project showcases
- `_posts/` - Blog entries

**Key directories**:
- `_pages/` - Static pages (about, cv, etc.)
- `_layouts/` - Page templates (single.html, talk.html, etc.)
- `_includes/` - Partial templates (author-profile, footer, etc.)
- `_sass/` - SCSS stylesheets
- `_data/navigation.yml` - Top navigation menu configuration
- `files/` - Downloadable PDFs and documents (served at /files/filename.pdf)
- `images/` - Image assets
- `markdown_generator/` - Python scripts to generate markdown from TSV/BibTeX

## Content Frontmatter

Teaching pages use this frontmatter structure:
```yaml
---
title: "COURSE NUMBER :: Course Title"
collection: teaching
type: "Undergraduate Course"
permalink: /teaching/YYYY-semester-COURSENUMBER
venue: "University of Georgia"
date: YYYY-MM-DD
---
```

All collections follow similar patterns with `collection`, `permalink`, and `date` fields.

## Site Configuration

Main settings are in `_config.yml`. Changes to this file require server restart. Use `_config.dev.yml` for local development overrides.

Collections defaults (layouts, sharing, comments) are configured in the `defaults:` section of `_config.yml`.
