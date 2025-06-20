# 🎨 CSS Color Markers

This project visually displays a vertical stack of colorful "marker-style" boxes using HTML and CSS. Each box is styled with gradients and shadows to resemble a colorful marker. It's an aesthetic and interactive way to explore CSS gradients, layout, and design.

---

## 📄 Contents

- `index.html` — HTML structure of the color boxes.
- `style.css` — Styling for each colored box using CSS gradients and effects.

---

## 🧱 Project Structure

### HTML Overview

The HTML file contains:

- A `<main>` section with a `<div>` containing multiple nested `div`s representing individual markers.
- Each marker is made up of:
  - A `.space` block (for spacing/padding).
  - A `.cover` block (representing a semi-transparent section with a black double border).
- Each color (`.red`, `.green`, `.blue`, etc.) is defined as a class on a parent `div`.

### CSS Features

- Each color class:
  - Has a height of 200px and width of 20px.
  - Uses `linear-gradient` for a dynamic, smooth color transition.
  - Includes `box-shadow` to make it appear glowing or vibrant.
- The `.cover` block:
  - Mimics the marker's cap or label.
  - Uses `rgba` for semi-transparency and a double black border.
- On hover, each marker shows a pointer cursor, giving interactive feedback.

---

## 🖍 Colors Included

- Red
- Orange
- Yellow
- Green
- Blue
- Indigo
- Violet
- Purple
- Pink
- Silver
- Gold
- Beige
- Brown
- Grey
- Black
- White

---

## 🔧 How to Use

1. Clone or download this repository.
2. Open `index.html` in any browser.
3. You’ll see a list of vertically stacked, colorful markers.
4. You can add or edit the colors by modifying the CSS rules in `style.css`.

---

## 📸 Preview

You’ll see vertical bars representing each color with a glowing, gradient look and a cap-like overlay.

---

## 💡 Customization Ideas

- Add labels or tooltips on hover.
- Make the markers clickable to show color values.
- Animate gradients or box shadows for visual effects.
- Group by shades or themes.

---

## 📜 License

This project is free to use for educational and personal projects.

---

## ✍️ Author

Created by Fathima Azha. Inspired by CSS design and color theory exercises of freecodecamp.

