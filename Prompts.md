# PROMPTS.md

## Learning Process and Research Notes

Before building this project, I spent time understanding the core web development concepts required in the assignment rather than directly implementing the solution.

## Concepts Studied

### 1. CSS Variables (Design Tokens)

I learned how CSS custom properties can be used to maintain a consistent color scheme throughout a project.

Topics explored:

* `:root` selector
* CSS custom properties
* Reusable color tokens
* Theme consistency

Applied in project:

```css
:root {
    --brand-primary: #8B0000;
    --brand-secondary: #F5F0E8;
}
```

---

### 2. CSS Flexbox

I studied Flexbox to understand how to center content both vertically and horizontally.

Key concepts:

* `display: flex`
* `justify-content`
* `align-items`
* Flex container vs flex items

Applied in the Hero section to center:

* Event title
* Description
* Call-to-action button

Reference:
https://www.youtube.com/watch?v=JJSoEo8JSnc

---

### 3. CSS Grid

I researched CSS Grid for creating responsive multi-column layouts.

Key concepts:

* `display: grid`
* `grid-template-columns`
* `gap`
* Responsive grid structures

Applied in the Author Event section to create a two-column layout.

Reference:
https://www.youtube.com/watch?v=9zBsdzdE4sM

---

### 4. Responsive Web Design

I studied how media queries help adapt layouts for smaller screens.

Key concepts:

* Breakpoints
* Mobile-first thinking
* Responsive layouts
* Screen width handling

Applied in project:

```css
@media (max-width: 768px) {
    .author-grid {
        grid-template-columns: 1fr;
    }
}
```

Reference:
https://www.youtube.com/watch?v=srvUrASNj0s

---

### 5. CSS Transitions and Hover Effects

I explored transitions to improve user interaction and visual feedback.

Key concepts:

* `transition`
* `transform`
* `scale()`
* Hover states

Applied on:

* Author images
* Author cards
* CTA button

---

### 6. Semantic HTML

I reviewed semantic HTML practices to improve structure and accessibility.

Elements used:

* `<header>`
* `<main>`
* `<section>`
* `<h1>` to `<h3>`
* `<p>`
* `<img>`

Benefits:

* Better accessibility
* Improved readability
* Cleaner document structure

---

## Development Approach

1. Created project structure according to the assignment requirements.
2. Implemented design tokens using CSS variables.
3. Built the Hero section using Flexbox.
4. Added the author showcase using CSS Grid.
5. Implemented hover animations and transitions.
6. Added responsive behavior using media queries.
7. Tested layout on different screen sizes.
8. Uploaded the project to GitHub and configured GitHub Pages deployment.

---

## Challenges Faced

* Understanding the difference between Flexbox and Grid and deciding where each should be used.
* Adjusting image scaling effects to avoid layout shifts.
* Ensuring the author section remained responsive on mobile devices.
* Maintaining consistent spacing and typography across sections.

---

## Outcome

Through this project, I gained practical experience with:

* HTML5 structure
* CSS variables
* Flexbox
* CSS Grid
* Responsive design
* Media queries
* CSS transitions
* Git and GitHub workflow
* GitHub Pages deployment

This project was completed after studying the above concepts and applying them to satisfy the requirements specified in the Technical Requirements Document (TRD).
