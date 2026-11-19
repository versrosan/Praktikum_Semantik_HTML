# Development Checklist

## Phase 1: Documentation
- [x] Create **AGENTS.md** with project guidelines.
- [x] Create **CLAUDE.md** with Claude-specific instructions.
- [x] Write **docs/PRD.md** - product requirements.
- [x] Write **docs/DESIGN.md** - design specification.
- [x] Write **docs/TECH-STACK.md** - technical stack description.
- [x] Review all documentation for consistency and completeness.

## Phase 2: HTML Structure
- [x] Set up `index.html` with semantic HTML skeleton (header, nav, main, sections, footer).
- [x] Add content for each required section (hero, products, services, members, contact).
- [x] Ensure proper heading hierarchy and alt attributes for images.
- [x] Implement all 12 required semantic elements (header, nav, main, section, article, aside, figure, figcaption, details, summary, time, footer).
- [x] Use `<address>` for contact information.
- [x] Zero `<div>` elements used.

## Phase 3: CSS Styling
- [x] Create `style.css` with dark theme colors, typography, and layout styles.
- [x] Implement responsive grid for product cards.
- [x] Style navigation, hero banner, service icons, member cards, and footer.
- [x] Add hover effects and focus outlines for accessibility.
- [x] Style `<details>`, `<summary>`, `<aside>`, and visible `<figcaption>` elements.

## Phase 4: Responsive Design
- [x] Write media queries for desktop, tablet, and mobile breakpoints.
- [x] Layout tested for desktop (>=1024px), tablet (768-1023px), and mobile (<=480px).
- [x] Navigation collapses to vertical list on mobile.

## Phase 5: Testing and Review
- [x] Semantic audit: all 12 required elements present and used correctly.
- [x] Anchor links: all 5 nav hrefs resolve to existing section IDs.
- [x] Images: 11/11 have alt attributes.
- [x] Heading hierarchy: h1 > h2 > h3, no skipped levels.
- [x] `<time>` elements have valid `datetime` attributes (4 instances).
- [x] `<details>` elements contain `<summary>` as first child (4 instances).
- [x] `<aside>` contains complementary promo content.
- [x] `<figcaption>` elements are visible and descriptive.
- [ ] Validate HTML with W3C validator (requires online tool).
- [ ] Validate CSS with a CSS validator (requires online tool).
- [ ] Perform visual inspection on desktop and mobile.
- [ ] Conduct accessibility checks (colour contrast verification).
