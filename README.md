# Web Programming – Assignment 2

## Theme
This project demonstrates how a single HTML document can produce two completely different visual layouts using two separate CSS stylesheets.  
The page contains six labeled boxes (A–F), and switching between *styleA.css* and *styleB.css* transforms the entire layout.

---

## File Organization

### 1. `index.html`
- Contains all six box elements.
- Links to either `styleA.css` or `styleB.css` depending on which version is needed.

### 2. `styleA.css`
Implements **Version A**:
- Vertical layout
- 6 boxes with equal vertical spacing
- Alternating colors
- Final box with special styling
- Uses CSS Flexbox

### 3. `styleB.css`
Implements **Version B**:
- First 5 boxes horizontal in the top-left
- No wrapping when resizing window
- Box F fixed in the bottom-right corner
- Hover effects (color + cursor)
- Dotted left border and padding

---

## Challenges Faced
- Ensuring equal spacing in Version A using Flexbox.
- Preventing wrapping of horizontal boxes in Version B.
- Correctly positioning the last box in the bottom-right using `position: fixed`.
- Matching all required dimensions, colors, and behaviors exactly as specified.

---