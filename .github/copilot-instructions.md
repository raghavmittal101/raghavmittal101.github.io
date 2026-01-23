# Copilot Instructions for AI Agents

## Project Overview
This repository is a personal or academic website, primarily built as a static HTML/CSS site. The main entry point is `index.html`. There are no build scripts, package managers, or complex frameworks present—customization is done directly in HTML and CSS.

## Key Patterns & Structure
- **Single Page Structure:** All content is managed in `index.html`. There are no subdirectories for components, assets, or scripts by default.
- **Content Blocks:** Major sections (e.g., papers, experience, education) are organized as repeated HTML blocks with class names like `.paper-item`, `.experience-item`, etc.
- **Styling:** CSS is either inline in the HTML or in `<style>` tags. There is no external CSS file by default.
- **No JavaScript:** The site does not use JavaScript for interactivity or dynamic content.

## Customization & Conventions
- **Add new content** by duplicating and editing existing HTML blocks (e.g., to add a new paper, copy a `.paper-item` div).
- **Styling conventions:**
  - Use class names like `.paper-item`, `.project-item`, `.education-item` for visually distinct sections.
  - Maintain consistent padding, margin, and border-radius as seen in the provided CSS.
  - Backgrounds are typically white for content blocks, with subtle borders or shadows for separation.
- **Awards/Highlights:** Use `<span>` with inline styles for special highlights (e.g., awards in paper listings).

## Developer Workflow
- **Edit and preview:**
  - Open `index.html` in a browser to preview changes.
  - No build or deploy steps are required—just save and refresh.
- **No tests or automation:** There are no test scripts, CI/CD, or build tools in this repo.

## Examples
- To add a new paper:
  1. Copy an existing `<div class="paper-item">` block.
  2. Update the title, authors, venue, and links as needed.
- To adjust styles, edit the CSS in the `<style>` section of `index.html`.

## External Integrations
- **Links:** External resources (e.g., presentations) are linked with `<a target="_blank">` for new tab behavior.
- **No analytics, forms, or scripts** are present by default.

## Summary
This is a minimal, static, single-file HTML/CSS site. All changes are made directly in `index.html`. Follow the established block and class patterns for consistency. No build, test, or deployment automation is present.
