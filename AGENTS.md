# Repository Guidelines

## Project Structure & Module Organization
This repository is a personal learning and study tracker that documents what you are working on.
Current structure:
- `README.md`: the primary record of learning topics, study schedules, and links.
- `AGENTS.md`: contributor guidance for maintaining this repository.

If you add more materials later, keep them grouped by purpose (for example, `notes/` for study notes and `projects/` for project write-ups).

## Build, Test, and Development Commands
There are no build or runtime commands defined. This repository is documentation-focused.
If you introduce tooling later, document the exact command and intent. Examples:
- `npm run build`: generate a static site from Markdown.
- `npm test`: run any automated checks or linters.

## Coding Style & Naming Conventions
- Use Markdown for all content updates.
- Keep headings short and sentence-cased.
- Bilingual sections are fine when they improve clarity; keep the overall tone consistent.
- Use descriptive filenames (`AGENTS.md`, `README.md`) and keep line lengths readable.

If code is introduced later, define indentation and formatter/linter rules (e.g., 2 spaces for YAML, 4 spaces for Python, `prettier` for JS).

## Testing Guidelines
No tests are configured. If checks are added later:
- Document the framework or tooling (e.g., markdownlint) and how to run it.
- Use clear, descriptive test or rule names.
- Set coverage expectations only when reporting is available.

## Commit & Pull Request Guidelines
Recent commits use simple, imperative messages like `Update README.md`. Follow the same pattern unless a new convention is introduced.

Pull requests should include:
- A short summary of changes (what learning items were added or updated).
- Linked issues (if applicable).
- Screenshots for visual or Markdown layout changes.

## Security & Configuration Tips
Do not add secrets or personal tokens to this repository. For external links in Markdown, prefer HTTPS and ensure the destination is trustworthy.

## Content Update Tips
- Keep the learning/study list current and remove stale entries.
- Use consistent date formats (e.g., `YYYY.MM.DD`) for schedules.

## Agent-Specific Instructions
When adding new files or sections, keep the document concise (200–400 words) and update this guide to match the repository’s evolving structure.
