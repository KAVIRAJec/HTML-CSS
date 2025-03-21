# Pure CSS Carousel/Slider

## Overview
This project demonstrates the creation of a **Pure CSS Carousel/Slider**. The carousel cycles through slides automatically using CSS animations and allows manual slide selection using radio buttons and the `:checked` pseudo-class. The design is responsive and visually engaging, with smooth transitions and navigation dots for manual control.

---

## Features
- **Auto-Sliding Carousel**:
  - Uses `@keyframes` animations to cycle through slides automatically.
- **Manual Slide Selection**:
  - Hidden radio buttons and the `:checked` pseudo-class allow users to manually select slides.
- **Navigation Dots**:
  - Interactive dots for manual navigation, with hover effects and active state highlighting.
- **Responsive Design**:
  - The carousel adapts to various screen sizes, ensuring a consistent user experience.

---

## File Structure
```
Task-7/
├── index.html   # HTML file for the carousel
└── styles.css   # CSS file for styling the carousel
```

---

## Workflow

### 1. **HTML Structure**
- **Radio Buttons**:
  - Hidden radio buttons (`<input type="radio">`) are used for manual slide selection.
  - The `checked` attribute ensures the first slide is active by default.
- **Slides**:
  - Each slide is wrapped in a `<div>` with a unique `id`.
  - Images are displayed inside the slides.
- **Navigation Dots**:
  - `<label>` elements act as clickable dots, linked to the radio buttons using the `for` attribute.

### 2. **CSS Styling**
- **Carousel**:
  - The `.slides` container uses `display: flex` to arrange slides horizontally.
  - The `@keyframes` rule creates an auto-sliding effect.
- **Manual Navigation**:
  - The `:checked` pseudo-class is used to control the visibility of slides.
  - Navigation dots change color when the corresponding slide is active.
- **Responsive Design**:
  - The carousel adapts to the screen width with `width: 100%` and responsive images.

---
