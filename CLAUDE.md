# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an Obsidian knowledge vault and personal writing platform focused on personal development topics including agency, discipline, identity, and psychology. The vault serves both as a knowledge base and source content for a published website.

## Architecture

- **Content Vault**: Topic-based folders containing markdown articles (Agency/, Discipline/, Identity/, Psychology/, Fitness/, etc.)
- **Brand Assets**: Brand identity, storytelling materials, and content strategy in Brand/
- **Writing Pipeline**: Drafts, edits, and ideas organized in Writing/
- **Published Content**: Separate sync to `remote-website` directory via obsidian-git plugin
- **Templates**: Reusable note templates in Templates/

## Key Files

- `Index.md` - Website homepage/entry point
- `Hopecore Tracker.md` - Motivational quotes tracker with completion status
- `Apps.md` - Application ideas and concepts

## Obsidian Conventions

- **Links**: Uses WikiLink syntax `[[Note Name]]` for internal cross-references
- **Theme**: Minimal theme with forest green accent (#2e8b57)
- **Fonts**: Sans Serif Collection for interface and body

## Git Workflow

- **Automated backups**: Commits via obsidian-git plugin with message format "vault backup: {{date}}"
- **Branch pattern**: Feature work uses `claude/` branch prefix for AI-assisted content
- **Main branch**: master
- **Remote**: https://github.com/ReedRawlings/ObsidianRepo.git

## Content Guidelines

- Articles track metadata: completion status, image needs, tone (positive/negative)
- Brand ethos: "The work is bigger than us", "Win, and help win", "It's never been easier to be an outlier"
- Target audience: Men aged 18-45 seeking self-improvement
- Core themes: Agency, discipline, identity transformation, intentional living

## Working with This Vault

When creating or editing articles:
1. Follow existing folder organization by topic
2. Use WikiLinks for cross-referencing related concepts
3. Maintain consistent formatting with existing articles
4. Check Hopecore Tracker.md for quote status when relevant
