# CSS Accordion Component

## Overview
This project demonstrates the creation of a **CSS Accordion Component** using the checkbox hack. The accordion allows users to expand and collapse content sections by clicking on headers. The implementation uses hidden checkboxes and the `:checked` pseudo-class to control the visibility of content, ensuring a smooth and interactive experience without JavaScript.

---

## Features
- **Expandable Sections**:
  - Each accordion section can be expanded or collapsed by clicking on its header.
- **Checkbox Hack**:
  - Hidden checkboxes control the open/closed state of each section.
- **Smooth Transitions**:
  - CSS transitions are used to animate the expansion and collapse of content areas.
- **Responsive Design**:
  - The accordion is styled to adapt to various screen sizes.

---

## File Structure
```
Task-8/
├── index.html   # HTML file for the accordion component
└── styles.css   # CSS file for styling the accordion
```

---

## Workflow

### 1. **HTML Structure**
- **Checkbox Hack**:
  - Hidden checkboxes (`<input type="checkbox">`) are used to control the open/closed state of each accordion section.
  - `<label>` elements act as clickable headers, linked to the checkboxes using the `for` attribute.
- **Content Sections**:
  - Each content section is wrapped in a `<div>` with the class `accordion-content`.

### 2. **CSS Styling**
- **Accordion Headers**:
  - Styled as clickable blocks with hover effects and active state highlighting.
- **Accordion Content**:
  - Initially hidden using `max-height: 0` and `overflow: hidden`.
  - Expanded when the corresponding checkbox is checked (`:checked` pseudo-class).
- **Transitions**:
  - Smooth expansion and collapse are achieved using the `transition` property.

---