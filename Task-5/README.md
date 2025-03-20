# Modal Popup Using the `:target` or Checkbox Hack

## Overview
This project demonstrates two implementations of a modal popup using pure CSS:
1. **`:target` Pseudo-Class**: Opens the modal when an anchor link is clicked.
2. **Checkbox Hack (`:checked`)**: Uses a hidden checkbox to toggle the modal's visibility.

Both implementations include a centered modal with an overlay backdrop and smooth transitions for appearance and disappearance.

---

## Features
- **Modal Popup**:
  - Opens and closes without JavaScript.
  - Includes a title, description, and close button.
- **Overlay Backdrop**:
  - A semi-transparent background that appears when the modal is active.
- **Two Implementations**:
  - `:target` pseudo-class.
  - Checkbox hack with `:checked` pseudo-class.

---

## File Structure
```
Task-5/
├── target.html   # Modal implementation using the `:target` pseudo-class
├── styles.css    # Styles for the `:target` implementation
├── checked.html  # Modal implementation using the checkbox hack
└── styles1.css   # Styles for the checkbox hack implementation
```

---

## Workflow

### 1. **Modal Using `:target`**
- **HTML**:
  - The modal is identified by an `id` (e.g., `id="modal"`).
  - Clicking an anchor link (`<a href="#modal">`) activates the `:target` pseudo-class.
  - Clicking a close button (`<a href="#">`) removes the `:target` state, hiding the modal.
- **CSS**:
  - The modal is hidden by default (`display: none`).
  - The `:target` pseudo-class sets `display: block` to show the modal.

### 2. **Modal Using Checkbox Hack**
- **HTML**:
  - A hidden checkbox (`<input type="checkbox" id="modal-toggle">`) is used to toggle the modal.
  - A `<label>` element acts as the trigger to open or close the modal.
- **CSS**:
  - The modal is hidden by default (`display: none`).
  - The `:checked` pseudo-class sets `display: block` to show the modal.

---
