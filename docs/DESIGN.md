# Design Specification

## Visual Direction
- Inspired by the provided **Techgear Landing Page** reference image.
- Dark theme overall with high contrast accents for readability.
- Clean, minimalistic layout suitable for a school project.

## Color Palette
| Role | Hex |
|------|-----|
| Background | `#121212` |
| Primary (accent) | `#ff9800` |
| Secondary (accent) | `#03a9f4` |
| Text – primary | `#ffffff` |
| Text – secondary | `#b0b0b0` |
| Card background | `#1e1e1e` |

## Typography
- **Font family:** `Helvetica, Arial, sans-serif` (web‑safe, no external imports).
- **Base font size:** 16 px (adjusts with viewport for responsiveness).
- **Headings:** Bold weight, larger size hierarchy (`h1` 2.5rem, `h2` 2rem, `h3` 1.5rem).
- **Body text:** 1rem, line‑height 1.5.

## Layout Structure
- **Header** (`<header>`): logo on the left, navigation `<nav>` with horizontal list.
- **Hero** (`<section id="hero">`): full‑width background, centered headline (`<h1>`), sub‑headline (`<p>`), and a call‑to‑action button (`<a>` styled as button).
- **Products** (`<section id="products">`): grid of `<article>` cards, each containing `<figure>` for image, `<h3>` for product name, and `<p>` for description.
- **Services** (`<section id="services">`): three columns with icons and short text.
- **Members** (`<section id="members">`): horizontal scroll of team member `<article>` cards.
- **Contact** (`<section id="contact">`): simple contact details and an optional static form layout.
- **Footer** (`<footer>`): copyright, secondary navigation links.

## Navigation Design
- Horizontal list of links inside `<nav>`; sticky at top on scroll.
- Visible focus outline for keyboard navigation.

## Hero Section
- Dark background with a subtle gradient overlay.
- Centralized text, centered both vertically and horizontally.
- CTA button uses the primary accent color.

## Product Cards
- `<article class="product-card">` with a `<figure>` image and caption.
- Card hover effect: slight elevation and accent border.
- Responsive grid: 4 columns on desktop, 2 on tablet, 1 on mobile.

## Services Section
- Icons (SVG or PNG) placed above short description.
- Flexbox layout that wraps on smaller screens.

## Members Section
- Circular avatar images inside `<figure>`.
- Name and role displayed under each avatar.
- Horizontal scrolling on mobile.

## Contact Section
- Simple layout with address, phone, email.
- No functional form processing – placeholder fields only.

## Footer
- Dark background matching header.
- Small text for copyright and links.
- Links have hover underline.

## Responsive Behavior
- **Desktop (≥1024 px):** multi‑column grids, full navigation bar.
- **Tablet (768‑1023 px):** two‑column product grid, stacked service columns.
- **Mobile (≤480 px):** single‑column layout, navigation collapses to a vertical list, hero text scales down, product cards full‑width.
- Use CSS media queries (`@media (max-width: 1024px)`, `@media (max-width: 480px)`).

---
*All design decisions aim to keep the markup semantic, the CSS simple, and the project manageable for SMK students.*