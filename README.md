# Safa Hearts - Bootstrap Migration (Week 3)

A migration of the Safa Hearts platform from vanilla CSS to Bootstrap 4.5.2, demonstrating framework integration skills.

**Original Vanilla CSS Version:** https://github.com/k7le-777/safa-hearts

---

## Project Context

This repository contains the Bootstrap-migrated version of Safa Hearts:
- **Week 2:** Built from scratch with vanilla HTML/CSS (see original repo above)
- **Week 3:** Migrated to Bootstrap framework (this repository)

---

## Live Sites

**This Version (Bootstrap):** later when finalised 
**Original Version (Vanilla CSS):** https://k7le-777.github.io/safa-hearts/

---

## Migration Status

🚧 **Currently migrating components to Bootstrap** 🚧

### Completed
- [x] Project setup and documentation
- [ ] Navigation → Bootstrap Navbar
- [ ] Card grids → Bootstrap Cards + Grid
- [ ] Forms → Bootstrap Form components
- [ ] Buttons → Bootstrap Button classes
- [ ] Utility classes implementation

---

## Technologies

- HTML5
- CSS3 + Bootstrap 4.5.2
- jQuery (required for Bootstrap JS)
- Custom CSS overrides for brand identity

---

## Bootstrap Components Used

1. Navbar with responsive hamburger menu
2. Card component with grid system
3. Form components with styling
4. Button components
5. Utility classes (spacing, alignment, colors)

---

## What Changed vs Original

**Replaced with Bootstrap:**
- Custom flexbox navigation → Bootstrap Navbar
- Custom card layouts → Bootstrap Cards + Grid
- Custom dropdown → Bootstrap Dropdown
- Custom form styling → Bootstrap Form components

**Kept Custom:**
- Green color scheme (brand identity)
- Hero section styling
- Mission/impact box designs
- Pseudo-element avatars
- CSS variables for custom theming

---

**2. Create BOOTSTRAP_MIGRATION.md (your working document):**
```markdown
# Bootstrap Migration Plan

**Start Date:** [Today's date]  
**Target Completion:** [7 days from now]

---

## Migration Objectives

1. Reduce custom CSS by ~60%
2. Implement Bootstrap responsive grid system
3. Add mobile hamburger menu
4. Use minimum 3 Bootstrap components
5. Apply Bootstrap utility classes
6. Maintain green brand identity

---

## Current Analysis

### Original Codebase Stats
- **Custom CSS:** ~1000 lines
- **Pages:** 5 (index, who-we-are, our-mission, services, contact)
- **Custom Components:** navbar, cards, forms, buttons, footer
- **Flexbox Layouts:** cards-grid, stats-grid, team-grid, services-grid

---

## Migration Schedule

### Day 1: Foundation (2-3 hours)
- [x] Create repository documentation
- [x] Set up git workflow strategy
- [ ] Add Bootstrap CDN to all HTML files
- [ ] Test that nothing breaks
- [ ] Commit: "feat: add bootstrap 4.5.2 cdn"

### Day 2: Navigation (3-4 hours)
- [ ] Migrate navbar to Bootstrap Navbar component
- [ ] Implement hamburger menu for mobile
- [ ] Test responsive breakpoints
- [ ] Update CSS overrides for green theme
- [ ] Remove old navbar CSS
- [ ] Commit: "refactor: migrate navigation to bootstrap navbar"

### Day 3: Card Grids (3-4 hours)
- [ ] Convert index.html cards to Bootstrap Cards
- [ ] Implement Bootstrap grid (row/col system)
- [ ] Migrate who-we-are.html value cards
- [ ] Migrate services.html service cards
- [ ] Remove old card CSS
- [ ] Commit: "refactor: convert card grids to bootstrap components"

### Day 4: Stats & Team (2-3 hours)
- [ ] Migrate stats grid to Bootstrap grid
- [ ] Convert team cards to Bootstrap cards
- [ ] Test equal height cards (h-100 class)
- [ ] Remove old grid CSS
- [ ] Commit: "refactor: migrate stats and team grids to bootstrap"

### Day 5: Forms (2-3 hours)
- [ ] Migrate contact form to Bootstrap form components
- [ ] Add Bootstrap form validation classes
- [ ] Test form inputs on mobile
- [ ] Update form CSS overrides
- [ ] Commit: "refactor: migrate contact form to bootstrap components"

### Day 6: Utility Classes & Cleanup (2 hours)
- [ ] Replace custom spacing with Bootstrap utility classes
- [ ] Replace custom text alignment with Bootstrap classes
- [ ] Migrate buttons to Bootstrap button classes
- [ ] Remove redundant CSS
- [ ] Commit: "refactor: apply bootstrap utility classes and cleanup css"

### Day 7: Testing & Documentation (2 hours)
- [ ] Test all pages on desktop/tablet/mobile
- [ ] Cross-browser testing
- [ ] Update README with final status
- [ ] Create before/after comparison
- [ ] Final commit: "docs: complete bootstrap migration documentation"

---

## Components Migration Tracking

### Navigation
- **Before:** Custom flexbox navbar, custom dropdown
- **After:** Bootstrap Navbar with hamburger menu
- **Status:** ⏳ Pending

### Card Grids
- **Before:** Custom flexbox grid system
- **After:** Bootstrap grid (row/col) + Card component
- **Status:** ⏳ Pending

### Forms
- **Before:** Custom form styling
- **After:** Bootstrap form components
- **Status:** ⏳ Pending

### Buttons
- **Before:** Custom btn-primary, btn-secondary classes
- **After:** Bootstrap button classes with overrides
- **Status:** ⏳ Pending

---

## CSS Reduction Target

**Current:** ~1000 lines custom CSS  
**Target:** ~400 lines (60% reduction)  
**Actual:** TBD

---

## Decisions Log

### Why Keep Custom Hero Section?
The hero section with background image and overlay is a unique brand element. Bootstrap doesn't provide a direct equivalent, so keeping custom CSS here makes sense.

### Why Keep Pseudo-element Avatars?
These demonstrate CSS pseudo-element skills and are simpler than adding actual images. Bootstrap has no avatar placeholder component.

### Why Override Bootstrap Colors?
The green color scheme is core to Safa Hearts brand identity. Bootstrap's default blue would require changing throughout.

---

## Testing Checklist

### Visual Testing
- [ ] Pages look similar to original
- [ ] Green theme maintained throughout
- [ ] Cards have proper shadows/borders
- [ ] Buttons maintain hover effects

### Functional Testing
- [ ] All navigation links work
- [ ] Dropdown opens/closes
- [ ] Forms inputs work
- [ ] Mobile menu expands/collapses

### Responsive Testing
- [ ] Desktop (1920px, 1440px, 1024px)
- [ ] Tablet (768px)
- [ ] Mobile (480px, 375px)
- [ ] Hamburger appears at lg breakpoint (992px)

### Cross-browser Testing
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge

---
