# Samuele Gonnella - Personal Portfolio Website

This repository contains the source code for the professional multi-page personal portfolio website of **Samuele Gonnella**, Junior Fullstack Web Developer and Trainee EMT.

## 🚀 Live Site
The site is optimized to be deployed as static files (e.g., GitHub Pages) with no build step required.

## 📁 Project Structure
The project is built using a semantic and modular architecture:

```text
/
├── index.html                   # Home Page
├── portfolio.html               # Portfolio Page (all projects showcased inline)
├── about.html                   # About Page (biography, tech stack, and contact details)
├── project-website.html         # Mobile Detail Page: Croce Verde Web Portal
├── project-app.html             # Mobile Detail Page: Volunteer Diary Android App
├── project-snake.html           # Mobile Detail Page: Snake Game
├── project-winapp.html          # Mobile Detail Page: Windows Cleaner Tool
├── css/
│   ├── style.css                # Base styling, tokens, variables, typography, and shared components
│   ├── desktop.css              # Desktop-specific layouts (screens >= 768px)
│   └── mobile.css               # Mobile-specific layouts and behavior (screens < 768px)
├── img/                         # Images and brand asset directory
└── docs/
    ├── PRD.md                   # Product Requirements Document
    ├── STRUCTURE.md             # File and CSS Architecture
    └── CONFORMITY.md            # Accessibility and W3C validation compliance
```

## 🛠️ Technology Stack & Web Standards
- **Core Structure**: Valid Semantic HTML5 (`<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **Styling**: Pure Vanilla CSS3 with a modular responsive layout (divided strictly between base tokens, desktop grids, and mobile flex layouts).
- **Interactivity**: Vanilla JavaScript for responsive navigation, hamburger menu overlays, and dynamic URL rewriting.
- **Standards & Accessibility**: Designed to be W3C and WCAG 2.1 AA compliant (high color contrast, focus states, clear labels, and accessible navigation).

## 📱 Responsive Link Behavior
To optimize the user experience across all devices, this site implements a dynamic link rewriting pattern:
- **Desktop (>= 768px)**: Project cards navigate to detailed anchor sections inline on the `portfolio.html` page.
- **Mobile (< 768px)**: Tapping any project card navigates directly to dedicated, mobile-optimized detail pages (`project-*.html`).
- This behavior is handled dynamically by a Vanilla JavaScript listener listening to page load and viewport resize events.

## 📄 CV and License
- The original repository `README.md` has been renamed to [CV.md](file:///c:/Users/rgonn/Desktop/gonnytech.github.io/CV.md) as a downloadable reference.
- The project is licensed under the MIT License. See [LICENSE](file:///c:/Users/rgonn/Desktop/gonnytech.github.io/LICENSE) for more details.
