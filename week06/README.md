# Week 06 - Interactive Geometry Angle Visualizations

> Explore the relationship between **rectangle angles**, **triangle angles**, **circle geometry**, and **interior angle sums** through hands-on interactive demos built with HTML5 Canvas.

---

## 🚀 Live Demos

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Rectangle%20Interior%20Angles-e74c3c?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/rectangle_angles.html)

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Triangle%20Interior%20Angles-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/triangle_interior_angles.html)

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Right%20Triangle%20on%20Circle-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/right_angles.html)

[![Open Demo 4](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Angle%20Control%20with%20Buttons-9b59b6?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/change_angle.html)

---

## 📁 Files

| # | File | Description |
|---|------|-------------|
| 1 | **`rectangle_angles.html`** | Interactive rectangle with 4 draggable vertices, all angles fixed at 90° |
| 2 | **`triangle_interior_angles.html`** | Interactive triangle with 3 draggable vertices |
| 3 | **`right_angles.html`** | Right triangle inscribed in a circle with draggable endpoint |
| 4 | **`change_angle.html`** | Circle angle with increase/decrease buttons and reset |

---

## 📖 Overview

### 1. `rectangle_angles.html` — Interactive Rectangle Interior Angles

Drag any of the four vertices (**A**, **B**, **C**, **D**) to resize the rectangle. Every interior angle is always maintained at **90°**, and the sum is always **360°**.

**Features:**
- Four draggable vertices (A=red, B=blue, C=green, D=yellow)
- Right-angle square symbol drawn at each corner
- **90°** label at every vertex with color coding
- Interior angle sum always shows **∠A + ∠B + ∠C + ∠D = 360°**
- Dashed diagonal lines with center mark
- Edge length labels on each side
- Dimension panel: width, height, diagonal, and area
- Opposite corner stays fixed when dragging — rectangle constraint always maintained
- Touch support for mobile devices

---

### 2. `triangle_interior_angles.html` — Interactive Triangle Interior Angles

Drag any of the three vertices (**A**, **B**, **C**) to reshape the triangle and watch the interior angles update in real time.

**Features:**
- Three draggable vertices with color-coded angle arcs
- Displays **α** (red), **β** (blue), **γ** (green) with arc visualization
- Live calculation of **α + β + γ = 180°** (interior angle sum)
- Edge lengths displayed on each side
- Touch support for mobile devices

---

### 3. `right_angles.html` — Right Triangle on a Circle

A right triangle is inscribed in a circle. The **endpoint** moves along the circumference while maintaining a **90° angle at point A**.

**Features:**
- Circle with center, start, and endpoint markers
- Draggable **end** point constrained to the circle (0° – 360°)
- Fixed right angle (**β = 90°**) at point A with square symbol
- Labeled triangle sides: **radius = 1** (hypotenuse), **h** (horizontal), **center** (vertical)
- Angle arcs for **α** (at Center) and **γ** (at End)
- Interior angle sum display: **α + β + γ = 180°**

---

### 4. `change_angle.html` — Angle Control with Buttons

Same right-triangle-on-circle concept as Demo 3, enhanced with **button controls** for precise angle adjustments.

**Features:**
- All features from `right_angles.html`, plus:
- **Increase buttons:** +1°, +5°, +10°, +45°
- **Decrease buttons:** −1°, −5°, −10°, −45°
- **Reset button:** instantly returns endpoint to 0°
- Combines drag interaction with button-based control

---

## 🎯 Key Concepts Demonstrated

| Concept | Description |
|---------|-------------|
| **Rectangle Angle Sum** | The sum of interior angles of any rectangle is always **360°** (4 × 90°) |
| **Triangle Angle Sum** | The sum of interior angles of any triangle is always **180°** |
| **Right Angle** | An angle of exactly **90°**, shown with the square symbol |
| **Right Triangle** | A triangle with one angle fixed at **90°** |
| **Circle Geometry** | Right triangle inscribed in a circle with hypotenuse as radius |
| **Complementary Angles** | In a right triangle, **α + γ = 90°** (the two non-right angles) |

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — all rendering done via the Canvas 2D API
- **Vanilla JavaScript** — no external libraries or frameworks
- **CSS3** — responsive layout with Google Fonts (DM Sans, JetBrains Mono)
- **Touch Events** — full mobile/tablet support

---

## 💡 How to Use

1. **Click and drag** the highlighted points to change angles interactively
2. Watch the **angle values** and **interior sum** update in real time
3. In Demo 1, drag any corner to resize the rectangle — all angles stay at 90°
4. In Demo 4, use the **+/− buttons** for precise angle increments
5. Hit **Reset 0°** to return to the starting position

---

## 📂 Project Structure

```
week06/
├── README.md
├── rectangle_angles.html           ← Demo 1: Rectangle with 4 right angles
├── triangle_interior_angles.html   ← Demo 2: Draggable triangle
├── right_angles.html               ← Demo 3: Right triangle on circle
└── change_angle.html               ← Demo 4: Button-controlled angle
```

---

## 📄 License

This project is for educational purposes. Feel free to use and modify.
