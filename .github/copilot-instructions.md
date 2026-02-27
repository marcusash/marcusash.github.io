# Copilot Instructions: marcusash.github.io

> Read this before every task.

## What This Project Is

Personal brand and portfolio site for Marcus Ash, CVP of Design at Microsoft. Hosted on GitHub Pages at marcusash.github.io.

## Tech Stack

- **HTML + CSS + minimal JS** for the site. No frameworks, no build step, no CDN dependencies.
- **System fonts only**: Segoe UI Variable, Segoe UI, system-ui, Arial, sans-serif
- **Monospace**: Cascadia Code, Consolas, Courier New, monospace
- **No npm, no package.json, no build tools.** Static HTML served directly.

## Design System

This site uses the Forge design aesthetic with two themes (light and dark).

### Light Theme
- Background: #F8FAFC
- Surface/cards: #FFFFFF
- Text: #1E293B
- Muted text: #64748B
- Borders: #E2E8F0
- Accent: #FFCB05 (Maize)
- Navy: #1E293B

### Dark Theme
- Background: #0A0A0F
- Surface/cards: #12121A
- Text: #E2E8F0
- Muted text: #64748B
- Borders: #1E1E2E
- Accent: #4A90D9 (Architect Blue)

### Key Design Elements
- Monospace labels for section headers and eyebrows (uppercase, letter-spacing 0.12-0.16em)
- Card-based layout with subtle borders
- Maize (#FFCB05) accent stripe on hero in light mode
- Min 44px touch targets for mobile
- Mobile-first: 375px viewport minimum

## Content

- **Name**: Marcus Ash
- **Title**: CVP of Design, Microsoft
- **Bio**: Builder of tools, teams, and systems that help people do their best work.

### Projects (3 cards)
1. **Inkwell** — A terminal journaling app for focused daily writing. Built with Ink + TypeScript. Status: In Development. Link: github.com/marcusash_microsoft/journal. Accent: #4A90D9
2. **Motor City Math** — An adaptive algebra study tool built for Kai. Practice tests, answer keys, grade reports. Status: Live. Link: marcusash.github.io/motor-city-math. Accent: #93AEFF
3. **Motor City Chemistry** — Chemistry practice tests and answer keys for Kai. Standard 4.2 Ionic and Covalent Naming. Status: Live. Link: marcusash.github.io/motor-city-chemistry. Accent: #FB923C

## Rules

- No external CDN dependencies (everything self-contained)
- Valid HTML5
- WCAG AA contrast on all text
- System fonts only
- Mobile-first responsive design
- Light/dark theme toggle must persist via localStorage
- Default to system preference (prefers-color-scheme)
