<p align="center">
  <img src="assets/images/hero-architecture.svg" alt="Decode Labs — Modern architecture hero illustration" width="720">
</p>

<h1 align="center">Decode Labs</h1>

<p align="center">
  <strong>Designing tomorrow's architecture today.</strong><br>
  A modern, fully responsive architecture studio website built with semantic HTML5, CSS3, and vanilla JavaScript.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Responsive-Yes-2ea44f?style=for-the-badge" alt="Responsive">
  <img src="https://img.shields.io/badge/Framework-Free-555?style=for-the-badge" alt="No frameworks">
</p>

---

## Overview

**Decode Labs** is a single-page portfolio website for a fictional architecture design studio. It showcases professional UI/UX patterns, responsive layouts across all device sizes, and clean, maintainable code — making it ideal for internship evaluation and GitHub portfolio submission.

The site presents ten distinct sections — from a sticky navigation bar and hero banner to a contact form and multi-column footer — all crafted with accessibility and performance in mind.

---

## Live Preview

Open `index.html` in any modern browser to explore the full experience. No build step required.

---

## Highlights

| | |
|:---:|:---:|
| <img src="assets/images/project-1.svg" alt="Urban Horizon Tower" width="280"> | <img src="assets/images/project-2.svg" alt="Green Valley Residence" width="280"> |
| **Urban Horizon Tower** | **Green Valley Residence** |
| <img src="assets/images/project-3.svg" alt="Coastal Pavilion" width="280"> | <img src="assets/images/project-4.svg" alt="Skyline Office Hub" width="280"> |
| **Coastal Pavilion** | **Skyline Office Hub** |

---

## Features

### Page Sections
- **Sticky Header / Navbar** — Logo, navigation links, CTA button, and mobile hamburger menu
- **Hero Section** — Bold headline, supporting text, dual CTAs, and hero illustration
- **Features Section** — Three feature cards with icons, titles, and descriptions
- **Architecture Grid Section** — CSS Grid layout with sidebar and main content area
- **Services Section** — Four service cards with "Learn More" buttons
- **Project Showcase** — Six project cards in a CSS Grid gallery with hover zoom
- **Statistics Section** — Animated number counters triggered on scroll
- **Testimonials Section** — Three client testimonial cards with avatars
- **Contact Form** — Validated form with Name, Email, Subject, and Message fields
- **Footer** — Company info, quick links, social media icons, and copyright

### JavaScript Interactivity
1. Mobile hamburger menu with keyboard support (Escape to close)
2. Dark mode toggle with localStorage persistence
3. Smooth scrolling for in-page anchor links
4. Back-to-top button with scroll threshold
5. Contact form validation with inline error messages
6. Animated statistics counter using IntersectionObserver
7. Navbar scroll effect (shadow on scroll)

### Accessibility
- Skip-to-content link
- Semantic HTML5 landmarks
- Alt text on all images
- Form labels and ARIA attributes
- Visible focus indicators
- Keyboard-navigable interactive elements

---

## Technologies Used

- **HTML5** — Semantic markup with header, nav, main, section, article, aside, and footer
- **CSS3** — Custom properties, CSS Grid, Flexbox, animations, and media queries
- **JavaScript** — Vanilla ES6+ with modular init functions

> No React, Bootstrap, Tailwind, jQuery, or external frontend frameworks were used.

---

## Responsive Design

This project follows a **mobile-first** approach, building base styles for small screens and progressively enhancing for larger viewports.

| Breakpoint | Range | Key Adaptations |
|------------|-------|-----------------|
| Mobile | 0 – 767px | Single-column layouts, hamburger navigation, stacked hero |
| Tablet | 768px – 1023px | Two/three-column grids, visible nav links, expanded footer |
| Desktop | 1024px+ | Full multi-column layouts, side-by-side hero, architecture grid sidebar |

All layouts are tested to prevent horizontal scrolling and maintain visual integrity across screen sizes.

---

## Project Structure

```
project-1/
├── index.html          # Main HTML document
├── style.css           # All styles (mobile-first)
├── script.js           # Interactive functionality
├── README.md           # Project documentation
└── assets/
    ├── images/         # Hero, project, and avatar images
    │   ├── hero-architecture.svg
    │   ├── project-1.svg … project-6.svg
    │   └── avatar-1.svg … avatar-3.svg
    └── icons/          # Feature, service, and social icons
        ├── responsive.svg
        ├── grid.svg
        ├── architecture.svg
        ├── residential.svg
        ├── commercial.svg
        ├── interior.svg
        ├── planning.svg
        ├── linkedin.svg
        ├── twitter.svg
        ├── instagram.svg
        └── arrow-up.svg
```

---

## Visual Tour

<p align="center">
  <img src="assets/images/project-5.svg" alt="Riverside Cultural Center" width="340">
  &nbsp;&nbsp;
  <img src="assets/images/project-6.svg" alt="Minimalist Studio Loft" width="340">
</p>

<p align="center"><em>Project showcase cards with hover effects and CSS Grid layout</em></p>

<p align="center">
  <img src="assets/images/avatar-1.svg" alt="Client testimonial avatar" width="80">
  <img src="assets/images/avatar-2.svg" alt="Client testimonial avatar" width="80">
  <img src="assets/images/avatar-3.svg" alt="Client testimonial avatar" width="80">
</p>

<p align="center"><em>Testimonials section with client avatars and card layout</em></p>

---

## Installation

No build tools or package managers are required. To run locally:

1. **Clone or download** the project folder
2. **Navigate** to the `project-1` directory
3. **Open** `index.html` in any modern web browser

Alternatively, use the **Live Server** extension in VS Code for auto-reload during development:

1. Install the Live Server extension
2. Right-click `index.html` → "Open with Live Server"

---

## Future Improvements

- Add a blog section with article cards
- Convert to a multi-page site with client-side routing
- Integrate a headless CMS for dynamic project content
- Connect the contact form to a real backend API or email service
- Add image lazy loading and WebP format support
- Implement a project detail modal or lightbox gallery
- Add internationalization (i18n) support

---

## Author

**Easha**

---

## License

This project is created for educational and portfolio purposes as part of the **Decode Labs** internship program.
