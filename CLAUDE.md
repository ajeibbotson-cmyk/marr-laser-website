# Marr Laser & Skin Clinic — Full Website

## Project Type
Static multi-page website using self-contained HTML/CSS embeds for Webflow integration.

## Design System
- **Aesthetic**: Editorial premium, inspired by Reborne Longevity
- **Primary**: `#1a3a2a` (dark forest green)
- **Accent**: `#c9a84c` (gold)
- **Sage**: `#d5ddd7` (sage green backgrounds)
- **Off-white**: `#f7f5f0` (warm neutral)
- **Headings**: Georgia serif, uppercase, generous letter-spacing
- **Body**: Arial sans-serif

## Architecture
- Each section file in `sections/` is **self-contained** with inline `<style>` (for Webflow embed)
- Assembled HTML pages in root combine header + sections + footer for local preview
- BEM naming with `marr-` prefix
- CSS-only interactivity (no JS): `<details>`/`<summary>` accordions, checkbox hamburger menu
- Responsive breakpoints: 1200px, 991px, 767px, 478px

## File Structure
- `styles.css` — shared reset + tokens (local preview only)
- `sections/shared/` — header and footer (shared across pages)
- `sections/{page}/` — page-specific section files
- Root `*.html` — assembled preview pages

## Content
- Placeholder images use solid colour blocks with descriptive text
- Real clinic copy adapted from existing Marr Laser branding
- Phone: 028 XXX XXXX (placeholder)
- Address: Newry, Co. Down (placeholder)
