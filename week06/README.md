# Week 06 - Interactive Circle Angle & Triangle Visualizations

> Explore the relationship between **circle angles**, **right triangles**, and **interior angle sums** through hands-on interactive demos built with HTML5 Canvas.

---

## 🚀 Live Demos

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Triangle%20Interior%20Angles-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/triangle_interior_angles.html)

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Right%20Triangle%20on%20Circle-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/right_angles.html)

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Angle%20Control%20with%20Buttons-9b59b6?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/change_angle.html)

---

## 📁 Files

| # | File | Description |
|---|------|-------------|
| 1 | **`triangle_interior_angles.html`** | Interactive triangle with 3 draggable vertices |
| 2 | **`right_angles.html`** | Right triangle inscribed in a circle with draggable endpoint |
| 3 | **`change_angle.html`** | Circle angle with increase/decrease buttons and reset |

---

## 📖 Overview

### 1. `triangle_interior_angles.html` — Interactive Triangle Interior Angles

Drag any of the three vertices (**A**, **B**, **C**) to reshape the triangle and watch the interior angles update in real time.

**Features:**
- Three draggable vertices with color-coded angle arcs
- Displays **α** (red), **β** (blue), **γ** (green) with arc visualization
- Live calculation of **α + β + γ = 180°** (interior angle sum)
- Edge lengths displayed on each side
- Touch support for mobile devices

---

### 2. `right_angles.html` — Right Triangle on a Circle

A right triangle is inscribed in a circle. The **endpoint** moves along the circumference while maintaining a **90° angle at point A**.

**Features:**
- Circle with center, start, and endpoint markers
- Draggable **end** point constrained to the circle (0.1° – 359.9°)
- Fixed right angle (**β = 90°**) at point A with square symbol
- Labeled triangle sides: **radius = 1** (hypotenuse), **h** (horizontal), **center** (vertical)
- Angle arcs for **α** (at Center) and **γ** (at End)
- Interior angle sum display: **α + β + γ = 180°**

---

### 3. `change_angle.html` — Angle Control with Buttons

Same right-triangle-on-circle concept as Demo 2, enhanced with **button controls** for precise angle adjustments.

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
| **Interior Angle Sum** | The sum of interior angles of any triangle is always **180°** |
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
3. In Demo 3, use the **+/−  buttons** for precise angle increments
4. Hit **Reset 0°** to return to the starting position

---

## 📂 Project Structure

```
week06/
├── README.md
├── triangle_interior_angles.html   ← Demo 1: Draggable triangle
├── right_angles.html               ← Demo 2: Right triangle on circle
└── change_angle.html               ← Demo 3: Button-controlled angle
```

---

## 📄 License

This project is for educational purposes. Feel free to use and modify.
