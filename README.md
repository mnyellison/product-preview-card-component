# Frontend Mentor - Product preview card component solution

This is a solution to the Product preview card component challenge on Frontend Mentor. The goal of this challenge was to build a responsive product preview card as close as possible to the original design, practicing mobile-first development and responsive image handling.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshots/screenshot.jpg)

### Links

- Solution URL: https://github.com/mnyellison/product-preview-card-component
- Live Site URL: https://product-preview-card-component-three.vercel.app/

---

## My process

### Built with

- Semantic HTML5
- CSS custom properties (Variables)
- Flexbox & CSS Grid
- Mobile-first workflow
- Responsive images using the `<picture>` tag

---

### What I learned

During this project, I practiced:

- **Mobile-first approach:** Structuring the entire layout thinking about smaller screens first, making the desktop transition much easier.
- **Responsive images:** Implementing the `<picture>` element to dynamically switch between mobile and desktop images directly in HTML, saving bandwidth and improving performance.
- **Smart Layout Tricks:** Using `overflow: hidden` on the card wrapper to automatically clip the product image corners, avoiding redundant `border-radius` rules during responsive changes.
- **Dynamic Spacing:** Using Flexbox combined with `margin-top: auto` on the attribution footer to organically handle the asymmetrical vertical layout required by the design without relying on rigid, magical pixel numbers.

### Project Architecture

To ensure a clean and scalable environment, the project was organized with a clear separation of concerns, moving the styles into a dedicated folder:

```text
├── css/
│   └── style.css          # Organized styles with CSS variables and media queries
├── images/                # All optimized asset images and SVGs provided by the challenge
├── index.html             # Clean semantic HTML5 structure with responsive <picture> implementation
└── README.md              # Project documentation and learning process
```

### Continued development

In future projects, I want to continue improving:

- Advanced responsive workflows using CSS Grid and Flexbox layouts.
- Working fluently with relative units like `rem` and `em` to ensure better accessibility.
- Writing scalable and isolated CSS styles by balancing semantic tags and clean class architectures.
- Practicing clean git architecture and history organization.

---

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io) - The platform that provided this challenge to practice front-end skills.
- [MDN Web Docs - The Picture Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - Helped me double-check the syntax for responsive graphics handling.

---

### AI Collaboration

I used Gemini during this project to:

- Audit and refactor my CSS for cleaner architecture, removing redundant styling properties.
- Clarify code architecture strategies, debating when to use global tag selectors vs dedicated CSS classes.
- Master responsive image delivery using the modern HTML `<picture>` tag.
- Correct structural spacing behaviors with automated flex margins to prevent layout breaks on small screens.
- Fine-tune my workflow and plan logical Git commit steps.

The AI collaborator helped me reason through architectural decisions, ensuring I understood why code changes were made rather than just copying solutions.

---

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/mnyellison
- GitHub - https://github.com/mnyellison
