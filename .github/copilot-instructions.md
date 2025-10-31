# Copilot Instructions for holbertonschool-headphones

## Project Overview
This repository contains static HTML and CSS files for a headphones-themed website. There is no backend, build system, or JavaScript integration. The project is organized by numbered versions, each with its own HTML and CSS files (e.g., `0-index.html`, `1-index.html`, etc.), likely representing progressive iterations or exercises.

## File Structure
- `0-index.html`, `1-index.html`, `2-index.html`, `3-index.html`: Main HTML files for each version.
- `0-styles.css`, `1-styles.css`, `2-styles.css`, `3-styles.css`: Corresponding CSS files for each HTML version.
- `images/`: Contains image assets used in the site.
- `README.md`: Currently empty; does not contain project instructions.

## Key Patterns and Conventions
- **Versioned Files:** Each HTML/CSS pair is independent. Do not assume shared styles or markup between versions unless explicitly stated.
- **No Build/Deploy Steps:** All files are static. No compilation, bundling, or deployment scripts are present or required.
- **No External Dependencies:** The project does not use npm, package managers, or external libraries. All assets are local.
- **Image Usage:** Reference images from the `images/` directory using relative paths in HTML and CSS.
- **Styling:** CSS files are plain and not modularized. Follow the structure and naming conventions found in existing CSS files when adding new styles.

## Developer Workflow
- **Preview:** Open HTML files directly in a browser to view changes. No local server is required.
- **Editing:** Make changes directly to the relevant HTML and CSS files. There is no code generation or automation.
- **Versioning:** When adding a new version, create a new pair of HTML and CSS files (e.g., `4-index.html`, `4-styles.css`).

## Examples
- To add a new page, copy an existing HTML/CSS pair and increment the version number.
- To update styles, edit the corresponding CSS file for the HTML version you are working on.
- To use an image, place it in the `images/` directory and reference it with a relative path (e.g., `images/headphones.png`).

## What Not To Do
- Do not introduce JavaScript, build tools, or external dependencies.
- Do not modify files across versions unless the change is intended for all versions.
- Do not add backend or server-side code.

---
For questions about project conventions, review the file structure and existing HTML/CSS files for examples. If anything is unclear or missing, ask for clarification or provide suggestions for improvement.
