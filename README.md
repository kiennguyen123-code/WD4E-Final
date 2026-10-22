# Explore Vietnam - Final Project (Web Design for Everybody)

This project is the Capstone / Final Project for the **Introduction to CSS3** course (University of Michigan on Coursera).

## Rubric Checklist Compliance

1. **Three Distinct HTML Pages:**
   - `index.html`: Home page with overview, history, and 2 featured images.
   - `destinations.html`: Features 6 destination cards (exceeds the 5 images requirement).
   - `gallery.html`: Photo gallery with 6 images.

2. **Skip to Main Content Link:**
   - Present on all three pages: `<a class="skip-link" href="#main">Skip to Main Content</a>`.
   - Uses `position: absolute` and `.skip-link:focus` so it is only visible when focused via keyboard Tab navigation.

3. **Navigation Styling:**
   - Uses `display: flex`, `background-color`, `padding`, `border-radius`, `box-shadow`, and smooth `:hover` / `:focus` transitions.

4. **Box Model for All Images:**
   - All `<img>` tags use `border: 3px solid`, `padding: 6px`, and `border-radius: 12px` with a crisp white frame background.

5. **CSS Grid:**
   - Implemented on `destinations.html` via `.grid-container` (`display: grid`, multi-column responsive layout, and gap).

6. **CSS Flexbox:**
   - Implemented on both `nav ul` and on `gallery.html` via `.flex-gallery` (`display: flex`, `flex-wrap: wrap`, and `justify-content`).

7. **Hover Pseudo-Class with Transitions & Transforms:**
   - Cards and gallery figures elevate smoothly with `transform: translateY(-8px) scale(1.02)` and enhanced box-shadows.

8. **nth-child Selector:**
   - Implemented in `gallery.html` via `.flex-gallery .gallery-item:nth-child(odd)` and `:nth-child(even)` to create alternating border shapes and colors.

9. **Accessibility & WAVE Validation:**
   - 100% compliant with WCAG AAA color contrast ratios.
   - Complete descriptive `alt` text on every image.
   - Valid semantic HTML5 markup.
