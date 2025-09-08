# Homepage
A fully responsive, accessible, and modern homepage built with HTML and CSS. Designed to showcase a portfolio, projects, and contact information with a flexible layout that adapts to desktops, laptops, tablets, and mobile devices. The site follows **WCAG 2.1 Level AA accessibility guidelines**.

---

## Features

- Fully **responsive layout** using `flex`, `min()`, `max()`, and `clamp()`
- Clean, modern **hero section** with profile image, skills row, and call-to-action button
- **Projects grid** showcasing multiple projects with:
  - GitHub repo links
  - Live demo links for each project
  - Interactive hover and focus effects
  - Fully responsive cards with flexible width and height
- **About section** with readable text and proper alignment
- **Contact section** with icons and text that wrap correctly on all screen sizes
- **Level AA accessible**:
  - Visible focus indicators for keyboard navigation
  - High color contrast for text and links
  - Descriptive `alt` text for images
  - ARIA labels for interactive elements
- Smooth scroll behavior and hover/focus effects
- Fully flexible layout; no hard-coded widths or heights
- Optimized for **all screen sizes**: desktop, laptop, tablet, and mobile

---

## Technologies Used

- **HTML5**
- **CSS3**
- Modern CSS functions: `clamp()`, `min()`, `max()`
- Flexbox & CSS Grid for layout
- Responsive images with `<picture>` and `srcset`

---

## Accessibility

This project follows **WCAG 2.1 Level AA** standards:

- Focusable elements (links/buttons) have **visible outlines**
- Color contrast meets minimum AA ratios
- Text wraps naturally on all screen sizes
- Semantic HTML is used (headings, sections, lists)
- All images have **meaningful alt text**
- Touch target sizes are sufficient for mobile

---

## Responsive Design

The layout adapts seamlessly across devices:

- **Desktop / Laptop:** Flexible columns, side-by-side hero and contact content
- **Tablet:** Icons and text remain visible; contact section stacks if needed
- **Mobile:** Single-column layout; text wraps properly next to icons and images scale proportionally

---

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/YourUsername/your-repo.git
