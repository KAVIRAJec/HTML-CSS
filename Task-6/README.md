# Tabbed Content Interface

## Overview
This project demonstrates the creation of a **Tabbed Content Interface** using pure HTML and CSS. The interface allows users to switch between different content sections by clicking on tabs. The implementation uses hidden radio buttons and the `:checked` pseudo-class to control the visibility of content, ensuring a smooth and interactive experience without JavaScript.

---

## Features
- **Tabbed Interface**:
  - Three tabs that display different content sections.
  - Tabs are styled with hover effects and active state highlighting.
- **Smooth Transitions**:
  - Content sections fade in with a smooth animation when switching tabs.
- **Responsive Design**:
  - The tabbed interface is centered and adapts well to various screen sizes.

---

## File Structure
```
Task-6/
├── index.html   # HTML file for the tabbed interface
└── styles.css   # CSS file for styling the tabbed interface
```

---

## Workflow

### 1. **HTML Structure**
- **Radio Buttons**:
  - Hidden radio buttons (`<input type="radio">`) are used to control which tab is active.
  - The `checked` attribute ensures the first tab is active by default.
- **Labels**:
  - `<label>` elements act as clickable tabs, linked to the radio buttons using the `for` attribute.
- **Content Sections**:
  - Each content section is wrapped in a `<section>` with a unique `id`.

### 2. **CSS Styling**
- **Tabs**:
  - Styled as a horizontal bar with equal-width labels.
  - The active tab is highlighted using the `:checked` pseudo-class.
- **Content**:
  - Only the content corresponding to the active tab is displayed (`display: block`).
  - Smooth transitions are added using the `@keyframes` rule.
- **Responsive Design**:
  - The tabbed interface is centered and adapts to smaller screens with a maximum width of 500px.

---
