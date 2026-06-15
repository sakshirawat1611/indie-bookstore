 
# Indie Bookstore Landing Page

## Project Overview

This project is a responsive static landing page created for an independent bookstore's upcoming author reading event. The website is built using only HTML and CSS, following the technical requirements specified in the Stretch Assignment.

The landing page highlights the event, showcases featured authors, and provides a clean, responsive user experience suitable for deployment on a basic shared hosting environment.

---

## Technologies Used

* HTML5
* CSS3
* CSS Flexbox
* CSS Grid
* CSS Variables (Design Tokens)
* Media Queries

---

## Project Structure

```text
indie-bookstore/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
└── Images/
    ├── author1.jpg
    ├── author2.jpg
    └── bookshelf.jfif
```

---

## Features Implemented

### Phase 1: File Structure & Design Tokens

* Created `index.html` and `css/style.css`.
* Defined design tokens using CSS custom properties:

```css
:root {
    --brand-primary: #8B0000;
    --brand-secondary: #F5F0E8;
}
```

---

### Phase 2: Hero Section

* Full-screen hero section with background image.
* Main headline and CTA button centered using CSS Flexbox.
* Overlay added for improved text readability.
* Responsive typography and button hover effects.

---

### Phase 3: Event Grid

* Author profiles displayed using CSS Grid.
* Two-column layout for desktop screens.
* Author cards include:

  * Author image
  * Author name
  * Author biography
* Smooth hover transitions applied to author images and cards.

---

### Phase 4: Responsive Design

* Media query implemented at `max-width: 768px`.
* Grid layout collapses into a single column on mobile devices.
* Hero content adjusts for smaller screens.

```css
@media (max-width: 768px) {
    .author-grid {
        grid-template-columns: 1fr;
    }
}
```

---

## Accessibility Enhancements

* Semantic HTML structure (`header`, `main`, `section`).
* Descriptive image alt text.
* Keyboard focus styling for the call-to-action button.
* Mobile-friendly responsive layout.

---

## Assignment Requirements Checklist

| Requirement                 | Status |
| --------------------------- | ------ |
| Raw HTML & CSS Only         | ✅      |
| Design Tokens in `:root`    | ✅      |
| Flexbox Hero Section        | ✅      |
| Background Image Hero       | ✅      |
| CTA Button                  | ✅      |
| CSS Grid Author Layout      | ✅      |
| Two-Column Desktop Layout   | ✅      |
| Hover Transitions           | ✅      |
| Mobile Media Query (768px)  | ✅      |
| Single Column Mobile Layout | ✅      |
| No HTML Tables Used         | ✅      |

---
