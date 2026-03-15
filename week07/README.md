# Week 07 - Pythagorean Theorem & Circle Equation Visualizations

> Explore the relationship between the **Pythagorean theorem** and **circle equations** through interactive demos built with HTML5 Canvas — from plotting integer solutions to moving circles with sliders.

---

## 🚀 Live Demos

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo%201-Pythagorean%20Circle%20(Points%20%26%20Reflections)-e74c3c?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week07/pythagorean_circle.html)

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo%202-Pythagorean%20Formula%20Proof%20Step%20by%20Step-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week07/pythagorean_proof.html)

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo%203-Circle%20Equation%20with%20Radius%20Slider-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week07/circle_radius.html)

[![Open Demo 4](https://img.shields.io/badge/▶%20Open%20Live%20Demo%204-Moving%20Circle%20with%20Center%20Sliders-27ae60?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week07/circle_center.html)

---

## 📁 Files

| # | File | Description |
|---|------|-------------|
| 1 | **`pythagorean_circle.html`** | Plot integer Pythagorean solutions on a circle — toggle A/B/C/D points and reflections |
| 2 | **`pythagorean_proof.html`** | Step-by-step formula proof: plug each point into x²+y²=r² and verify |
| 3 | **`circle_radius.html`** | Drag a slider to change radius 0→5, watch the circle equation update live |
| 4 | **`circle_center.html`** | Drag a and b sliders (−5 to 5) to move a circle of radius 5 across the plane |

---

## 📖 Overview

### 1. `pythagorean_circle.html` — Pythagorean Circle (Points & Reflections)

Plots the integer solutions A=(5,0), B=(4,3), C=(3,4), D=(0,5) on a coordinate grid and shows how reflecting them across axes fills a circle of radius 5.

**Features:**
- Step buttons: Original → y-axis → x-axis → Origin reflections, plus Show All
- A/B/C/D checkmark toggles to show or hide each point family
- Prominent axes with arrowheads and origin O always drawn
- Hover tooltip: shows coordinates and x²+y²=25 ✓ verification
- D skips y-axis reflection (lies on y-axis); A skips x-axis reflection (lies on x-axis)

---

### 2. `pythagorean_proof.html` — Formula Proof Step by Step

Walks through all 16 steps (4 original points × 4 reflections each) proving every point satisfies x²+y²=5² with the arithmetic shown in large type.

**Features:**
- ← Prev / Next → navigation, keyboard arrow key support
- Large 4-line formula proof per step: point coords → abstract formula → numbers plugged in → result ✓
- Skip steps explained when a reflection lands on the same point
- Dot progress tracker grouped by A/B/C/D
- Canvas plots each verified point as it is proven, accumulating on the circle

---

### 3. `circle_radius.html` — Circle Equation with Radius Slider

Shows x²+y²=r² with a live slider for r from 0 to 5. The circle grows and shrinks in real time.

**Features:**
- Live formula display: x²+y²=r²=value updates as slider moves
- Gold slider (0→5) with color-filled track
- Radius line drawn from origin to circle edge with r value label
- Sample point on circle showing x, y legs and x²+y²=r² ✓ check
- Axis ticks at ±r on all four axes update dynamically

---

### 4. `circle_center.html` — Moving Circle with Center Sliders

Shows `(x−a)²+(y−b)²=5²` with sliders for a and b (each −5 to 5). The circle of radius 5 moves across the grid.

**Features:**
- Two sliders: a (gold, shifts circle left/right) and b (purple, shifts up/down)
- Live formula with actual values plugged in, sign auto-adjusts (− or +)
- Dashed guide lines from origin to center (a, b) with axis tick labels
- Center dot labeled (a, b) moves with the circle
- Radius line and r=5 label always visible
- Layout: 10% header / 80% canvas / 10% controls

---

## 🎯 Key Concepts Demonstrated

| Concept | Description |
|---------|-------------|
| **Pythagorean Theorem** | For any right triangle: **a² + b² = c²** |
| **Circle Equation** | All points at distance r from origin satisfy **x² + y² = r²** |
| **Integer Solutions** | (5,0), (4,3), (3,4), (0,5) all satisfy x²+y²=25 |
| **Axis Reflections** | Reflecting (x,y) across y-axis gives (−x,y); across x-axis gives (x,−y) |
| **General Circle** | Circle centered at (a,b) with radius r: **(x−a)² + (y−b)² = r²** |
| **Radius as Hypotenuse** | The radius is the hypotenuse of the right triangle formed by x and y legs |

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — all rendering via the Canvas 2D API
- **Vanilla JavaScript** — no external libraries
- **CSS3** — responsive layout, `vh`-based proportions, Google Fonts (JetBrains Mono)

---

## 💡 How to Use

1. **Demo 1:** Click step buttons to reveal reflections; use A/B/C/D checkmarks to isolate each point family
2. **Demo 2:** Press **Next →** (or arrow keys) to step through each formula proof one by one
3. **Demo 3:** Drag the **gold slider** to grow or shrink the circle and watch x²+y²=r² update
4. **Demo 4:** Drag the **a slider** to move the circle horizontally, **b slider** to move it vertically

---

## 📂 Project Structure

```
week07/
├── README.md
├── pythagorean_circle.html    ← Demo 1: Integer solutions & reflections on circle
├── pythagorean_proof.html     ← Demo 2: Step-by-step formula verification
├── circle_radius.html         ← Demo 3: x²+y²=r² with radius slider
└── circle_center.html         ← Demo 4: (x−a)²+(y−b)²=25 with center sliders
```

---

## 📄 License

This project is for educational purposes. Feel free to use and modify.
