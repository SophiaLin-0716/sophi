# Copilot Instructions for This Codebase

## Overview
This project is a collection of static HTML files, likely for educational or demonstration purposes. The main entry point is `index.html`, with additional content organized under the `ch04/` directory.

## Project Structure
- `index.html`: Main landing page.
- `ch04/`: Contains multiple HTML files (e.g., `01.html`, `profile.html`, `feedback.html`) representing different sections or exercises.

## Key Patterns & Conventions
- **No build system or package manager**: All files are static HTML. There are no scripts, stylesheets, or external dependencies referenced in the root directory.
- **File naming**: Files in `ch04/` are named numerically or by topic (e.g., `05-1.html`, `product.html`).
- **No JavaScript or CSS frameworks**: All logic and styling (if any) are expected to be inline or within the HTML files themselves.
- **No backend or API integration**: The project is purely frontend and static.

## Editing Guidelines
- When adding new content, follow the existing naming conventions in `ch04/`.
- Keep all code self-contained within each HTML file unless a new shared resource is introduced.
- If introducing shared assets (CSS, JS), place them in a new directory (e.g., `assets/`) at the project root and update all relevant HTML files to reference them.

## Example: Adding a New Exercise
1. Copy an existing file in `ch04/` (e.g., `05-1.html`) as a template.
2. Rename it following the numeric or topic-based pattern (e.g., `06.html` or `summary.html`).
3. Update the content as needed.

## AI Agent Guidance
- Do not introduce build tools, frameworks, or package managers unless explicitly requested.
- Maintain the static, self-contained nature of the project.
- Reference and reuse patterns from existing HTML files for consistency.
- If unsure about a new pattern, prefer the simplest approach (plain HTML, inline CSS/JS).

## Notable Files
- `index.html`: Entry point.
- `ch04/profile.html`, `ch04/feedback.html`, etc.: Examples of individual content pages.

---
For questions or major changes, consult the project owner.
