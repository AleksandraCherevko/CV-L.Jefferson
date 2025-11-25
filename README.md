# Portfolio — One-Page Website (SPA)

Project goal Create a portfolio prototype that allows a student to easily and
effectively present their achievements, projects, and skills to potential
employers.

## 🚀 Key features

Responsive one-page layout (mobile, tablet, desktop)

Semantic HTML5 structure

Font loading (including the provided Impact font)

Optimized images with retina support and lazy-loading

SVG icons included via sprite

Fullscreen mobile burger menu

Smooth anchor scrolling

Projects list with "Load more" functionality

Reviews slider populated from backend (with error handling)

Contact form with client-side validation and POST submission to API

Modal confirmation on successful form submission

## API Reference

Backend documentation: `https://portfolio-js.b.goit.study/api-docs`

Typical endpoints used in the project:

`GET /reviews` — fetch reviews to display in the slider

`POST /requests` — submit a collaboration request from the contact form

Use the API docs for exact request/response shapes and error handling details.

## 📐 Responsiveness

Breakpoints defined in the design spec:

mobile: fluid layout from 320px, becomes adaptive from 360px

tablet: from 768px

desktop: from 1280px

Mobile navigation is a fullscreen overlay (burger menu). When open, page
scrolling is locked.

## Installation

```bash
git clone <repository-url>
cd project-folder
npm install
npm start
```

## ♿ Accessibility & Best Practices

Use semantic HTML5 elements (header, nav, main, section, article, footer)

Ensure keyboard accessibility for interactive components (menu, accordion,
slider, modal)

Provide aria-\* attributes and focus management for dynamic UI (trap focus in
modal, return focus on close)

Use alt attributes for images and descriptive labels for form fields
