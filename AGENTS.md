# AGENTS.md

## Project Context
- **Project Name:** SannGadget
- **Type:** Simple Gadget Store Landing Page for a school practical assignment.
- **Goal:** Demonstrate correct usage of HTML5 semantic elements while creating a clean, responsive landing page.

## Coding Standards
- Use **HTML5 semantic tags** (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`) wherever appropriate.
- Keep **CSS** in a separate `style.css` file; avoid inline styles.
- **No JavaScript** – the assignment focuses on static markup and styling.
- Limit the use of `<div>` and custom `class`/`id` attributes; only add them when a semantic element cannot convey the needed meaning.
- Follow **accessibility basics**: alt text for images, proper heading hierarchy, sufficient color contrast.
- Keep the code **readable**: consistent indentation (2 spaces), meaningful comments, and line length ≤ 120 characters.

## Semantic HTML Priorities
1. **Document Structure** – `<header>`, `<nav>`, `<main>`, `<footer>` must be present.
2. **Sectioning** – Use `<section>` for distinct page areas (hero, products, services, members, contact).
3. **Content Elements** – Prefer `<article>` for product cards, `<figure>`/`<figcaption>` for images.
4. **Navigation** – Use `<ul>` inside `<nav>` for menu items.

## Simplicity Rules
- Do **not** introduce JavaScript, build tools, or CSS preprocessors.
- Avoid extra wrapper `<div>`s; rely on semantic elements for layout.
- Use a **single stylesheet** (`style.css`).
- Keep the folder structure flat: `assets/`, `docs/`, `src/` (if needed).

## File Management Rules
- All documentation lives under the `docs/` folder.
- Source files (`index.html`, `style.css`) reside in the project root.
- Image assets go into `assets/`.
- Do **not** modify files outside the project directory.

## Development Workflow
1. **Documentation First** – Complete all docs (`AGENTS.md`, `CLAUDE.md`, PRD, DESIGN, TECH-STACK, TASKS) before writing any HTML/CSS.
2. **Review** – Each document must be reviewed for completeness and consistency.
3. **Implementation** – Only after documentation sign‑off, start coding the markup and styles.
4. **Validation** – Run the W3C HTML validator on `index.html` and a CSS validator on `style.css`.
5. **Commit** – Keep commits atomic (e.g., "Add documentation", "Add hero section markup").

## Testing Requirements
- Validate HTML5 compliance using the W3C validator.
- Visual inspection on desktop (minimum width 1024px) and mobile (max width 480px).
- Verify accessibility: screen‑reader friendly headings, alt attributes, and color contrast.
