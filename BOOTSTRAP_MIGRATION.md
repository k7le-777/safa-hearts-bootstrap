# Bootstrap Migration Plan

**Start Date:** [02-10-2025]  
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
- [x] Add Bootstrap CDN to all HTML files
- [x] Test that nothing breaks
- [x] Commit: "feat: add bootstrap 4.5.2 cdn"

### Day 2: Navigation (3-4 hours)
- [ ] Migrate navbar to Bootstrap Navbar component
- [x] Implement hamburger menu for mobile
- [x] Test responsive breakpoints
- [x] Update CSS overrides for green theme
- [x] Remove old navbar CSS
- [x] Commit: "refactor: migrate navigation to bootstrap navbar"

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
