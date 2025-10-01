# Safa Hearts - Community Support Platform
- A responsive, multi-page website connecting people who need help with those who want to give it, built with semantic HTML, CSS Flexbox, and CSS variables.

# 🎯 Project Overview
-  Safa Hearts is a community support platform designed to bridge the gap between individuals seeking assistance and compassionate volunteers. The website demonstrates modern web development practices including responsive design, flexbox layouts, and accessible form design.
- Live Site: [Add your deployment URL here]
- Repository: [Add your GitHub repo URL here]

## Features
- 5 Fully Responsive Pages: Home, Who We Are, Our Mission, Services, Contact
- Flexbox Grid Layouts: Cards, navigation, footer, and content sections
- CSS Variable System: Consistent theming and easy customization
- Interactive Elements: Dropdown navigation, hover effects, form validation
- Accessible Design: Semantic HTML, ARIA attributes, keyboard navigation support
- Mobile-First Approach: Breakpoints at 768px and 480px for optimal viewing

## 🛠️ Technologies Used
- HTML5 - Semantic markup with proper document structure
- CSS3 - Custom properties, Flexbox, media queries, pseudo-elements/classes
- No frameworks - Vanilla HTML/CSS to demonstrate fundamental skills

## 📄 License
- This project is for educational purposes. Feel free to reference for learning, but please don't submit as your own work.

# Project Reflections 💫

## Challenges Overcome
- Initially struggled with flexbox centering - researched and tested multiple solutions
- Learned about pseudo-elements through trial and error
- Discovered the importance of semantic HTML through refactoring

## Key Learnings
- CSS specificity rules (had to debug dropdown hover issues)
- How @media queries enable responsive design
- Why proper HTML structure matters for flexbox layouts

### 🎓 Learning Journey
Challenges Overcome
**Flexbox Alignment Issues**
Initially struggled with centering hero content when the HTML structure had nested divs. Learned that flexbox requires proper parent-child relationships and that absolute positioning can break flex alignment. Resolved by restructuring HTML so .hero-content was a direct flex child.
**Dropdown Menu Mechanics**
Took time to understand how position: relative on the parent and position: absolute on the dropdown created the positioning context. Debugged issues with opacity, visibility, and transform needing to work together for smooth animations. Added :focus-within for keyboard accessibility after researching WCAG guidelines.
**Pseudo-element Avatar System**
Originally tried using content: url() for icons in ::after pseudo-elements, which didn't work. Learned that background-image must be used instead, and that pseudo-elements need display: inline-block to accept transform properties. This taught me the differences between inline and block-level elements.
**Button Alignment in Cards**
Cards with varying text lengths caused buttons to appear at different heights. Discovered that adding display: flex, flex-direction: column, and margin-top: auto to the button creates consistent alignment. This was my "aha moment" understanding how flex-grow and auto margins work.
**CSS Variable Mismatches**
Had several instances where I referenced undefined variables (like --background-primary) causing silent failures. Learned to systematically check variable names and understand that CSS fails silently - requiring browser DevTools inspection to debug.


## **Key Learnings**
- Responsive Design Philosophy
Understanding that mobile-first design means starting with constraints and progressively enhancing for larger screens. Media queries aren't just about hiding/showing elements - they're about rethinking layouts entirely.
- CSS Specificity & Cascade
Encountered multiple cases where styles weren't applying due to specificity issues. Learned to use browser DevTools to trace which rules were being applied and why. Now understand the hierarchy: inline > ID > class > element.
- Semantic HTML Importance
Initially used generic <div> containers everywhere. Learned that <header>, <main>, <section>, <footer>, <nav> improve both accessibility and code organization. Screen readers rely on this structure.
- Form Accessibility
Discovered that <label for="id"> associations, required attributes, and proper input types aren't optional - they're essential for usability. Tested navigation using only keyboard (Tab key) to understand accessibility challenges.


### 🔧 Technical Decisions
-  **Why Flexbox Over Grid?**:
Chose Flexbox because the rubric specified it and it's ideal for one-dimensional layouts (rows or columns). Grid would be better for complex two-dimensional layouts, but Flexbox solved all layout needs here.
- **Single CSS File vs. Modular**
Kept all CSS in one file because the project size didn't warrant complexity of imports. Used clear section comments for organization. Would split into modules (components.css, layout.css, pages.css) for larger projects.
- **CSS Variables Strategy**
Defined color, spacing, and typography variables in :root for consistency. This made theme adjustments easy and reduced repetition. Named variables semantically (--green-primary, --spacing-lg) rather than by value (--color-1, --size-2).
- **Image Handling**
Used relative paths (img/filename.jpg) rather than absolute paths for portability. Would implement lazy loading and responsive images (<picture> element) for production deployment.

Built with 💚 by Ryan Burns
Spreading compassion through code

*This project is part of the Step9Up BootCamp curriculum and demonstrates fundamental web development skills.*