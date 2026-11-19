# Product Requirements Document (PRD)

## Project Overview
- **Name:** SannGadget
- **Type:** Simple Gadget Store Landing Page
- **Purpose:** School practical assignment to practice correct use of HTML5 semantic elements.
- **Assignment Title:** "Membuat Layout Website Sederhana Menggunakan HTML Semantic Elements"

## Background & Objectives
- Teach students how to structure a web page with semantic tags.
- Produce a clean, responsive landing page that showcases a small gadget store.
- Demonstrate accessibility basics (alt text, heading hierarchy, colour contrast).

## Target Users
- SMK (vocational high school) students learning front‑end web development.
- Instructor reviewing the assignment.

## Website Sections
1. **Header / Navigation** – Site logo and primary menu.
2. **Hero** – Eye‑catching banner with headline and call‑to‑action.
3. **Products** – Grid of product cards.
4. **Services** – Brief description of services offered.
5. **Members** – Showcase team members.
6. **Contact** – Simple contact information / form placeholder.
7. **Footer** – Copyright and secondary links.

## Functional Requirements
- All markup must use **HTML5 semantic elements** (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`).
- No JavaScript; the page is static.
- CSS lives in a single `style.css` file.
- Images are stored locally in `assets/`.
- The page must be **responsive**: layout adapts for desktop (≥1024 px) and mobile (≤480 px).
- Provide alt attributes for all images.
- Use a clear heading hierarchy (`h1` → `h2` → `h3`).

## Non‑Functional Requirements
- **Performance:** No external resources; all assets are local.
- **Accessibility:** Sufficient colour contrast, screen‑reader friendly structure.
- **Maintainability:** Simple folder layout, minimal class/id usage.
- **Cross‑Browser:** Works in modern browsers (Chrome, Edge, Firefox).

## Scope
**In‑Scope:**
- Semantic HTML markup.
- CSS styling (dark theme, responsive grid).
- Documentation (this PRD, DESIGN, TECH‑STACK, TASKS, AGENTS, CLAUDE).

**Out‑of‑Scope:**
- JavaScript interactivity.
- Backend or form handling.
- Asset optimization beyond basic sizing.

## Acceptance Criteria
- [ ] HTML validates without errors on the W3C validator.
- [ ] CSS validates without errors.
- [ ] All required sections are present and correctly marked up.
- [ ] Page displays correctly on both desktop and mobile viewports.
- [ ] Accessibility checklist passed (alt text, headings, contrast).
- [ ] Documentation files are complete, consistent, and reviewed.
