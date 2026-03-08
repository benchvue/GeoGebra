# Week 06 - Interactive Geometry Angle Visualizations

> Explore the relationship between **rectangle angles**, **triangle angles**, **circle geometry**, **interior angle sums**, and the **Pythagorean theorem** through hands-on interactive demos built with HTML5 Canvas.

---

## 🚀 Live Demos

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo%201-Rectangle%20Interior%20Angles-e74c3c?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/rectangle_angles.html)

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo%202-Triangle%20Interior%20Angles-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/triangle_interior_angles.html)

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo%203-Right%20Triangle%20on%20Circle-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/right_angles.html)

[![Open Demo 4](https://img.shields.io/badge/▶%20Open%20Live%20Demo%204-Pythagorean%20Theorem%20Step%20by%20Step-27ae60?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/Pythagorean.html)

[![Open Demo 5](https://img.shields.io/badge/▶%20Open%20Live%20Demo%205-Pythagorean%20Dynamic%20Triangle-f39c12?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/angle_Pythagorean-1.html)

[![Open Demo 6](https://img.shields.io/badge/▶%20Open%20Live%20Demo%206-Pythagorean%20Circle%20Radius%205%20(Fixed%20End)-16a085?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/angle_Pythagorean-2.html)

[![Open Demo 7](https://img.shields.io/badge/▶%20Open%20Live%20Demo%207-Pythagorean%20Circle%20Center%20Origin-8e44ad?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week06/angle_Pythagorean-3.html)

---

## 📁 Files

| # | File | Description |
|---|------|-------------|
| 1 | **`rectangle_angles.html`** | Interactive rectangle with 4 draggable vertices, all angles fixed at 90° |
| 2 | **`triangle_interior_angles.html`** | Interactive triangle with 3 draggable vertices |
| 3 | **`right_angles.html`** | Right triangle inscribed in a circle with draggable endpoint |
| 4 | **`Pythagorean.html`** | Step-by-step visual proof of the Pythagorean theorem (3-4-5 example) |
| 5 | **`angle_Pythagorean-1.html`** | Dynamic Pythagorean triangle — drag point along diameter, base & height update live |
| 6 | **`angle_Pythagorean-2.html`** | Pythagorean theorem on a circle (radius = 5, fixed left end) — drag C around full circle |
| 7 | **`angle_Pythagorean-3.html`** | Pythagorean theorem on a circle — hypotenuse from center (0,0) to C, drag full 360° |

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

### 4. `Pythagorean.html` — Pythagorean Theorem Step by Step

A guided 5-step visual proof of the Pythagorean theorem using the classic **3-4-5** right triangle.

**Features:**
- Step-by-step navigation (Step 1 → Step 5) with Previous / Next buttons
- **Step 1:** Right triangle with labeled sides a=3, b=4, c=5
- **Step 2:** Three squares drawn outward on each side (green, blue, red)
- **Step 3:** Grid lines inside each square showing area = side²
- **Step 4:** Circled number labels ①②③ with the live addition 9 + 16 = 25
- **Step 5:** Final formula **a² + b² = c²** with numeric proof
- Progress dots and animated panel transitions
- Paper-texture background with serif typography

---

### 5. `angle_Pythagorean-1.html` — Dynamic Pythagorean Triangle

An interactive Pythagorean diagram where the **right-angle vertex B slides left/right** along the base (x-axis), and the height always remains vertical using Thales' theorem.

**Features:**
- Drag the **purple point B** left or right along the horizontal baseline
- Base leg (green square, below baseline) and height leg (blue square, right) update dynamically
- Hypotenuse square (red, rotated) always faces outward
- Right-angle box at B with 90° label, adjusts direction per quadrant
- Live equation panel: **a² + b² = sum | c² = value** — always equal
- All squares guaranteed fully visible at all drag positions

---

### 6. `angle_Pythagorean-2.html` — Pythagorean on Circle, Radius 5, Fixed Left End

A Pythagorean theorem visualization on a **circle of radius 5** where point **I is fixed** at the left end of the diameter (−5, 0) and point **C moves freely around the full circle**.

**Features:**
- Full **360° drag** — point C moves through all four quadrants
- **Base always horizontal** (I → foot B on x-axis), **height always vertical** (B → C)
- Right angle always at B (foot of perpendicular from C to x-axis)
- Green square on base (a), blue square on height (b), red square on hypotenuse (c)
- Squares always outward — pre-computed world bounds ensure **no clipping ever**
- x/y axis with grid, corner labels D/E, F/G, H/I
- Live equation: **a² + b² = c²** updates in real time

---

### 7. `angle_Pythagorean-3.html` — Pythagorean on Circle, Hypotenuse from Center

The most general form: the hypotenuse always runs from the **circle center O = (0,0)** to the draggable point **C on the circle** (radius = 5). The foot B is always directly below/above C on the x-axis.

**Features:**
- **c = 5 always** (radius), so **c² = 25 always** — drag to verify
- Full **360° drag** through all four quadrants
- Coordinate grid with numbered axis ticks (−7 to +7)
- Green square on base O→B, blue square on height B→C, red square on hypotenuse O→C
- All squares always outward and fully on screen (symmetric ±8.4 world bounds)
- Right-angle box at B adapts its direction per quadrant
- Live equation: **a² + b² = 25 = c²** — always verified

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
| **Pythagorean Theorem** | For any right triangle: **a² + b² = c²** |
| **Thales' Theorem** | Any triangle inscribed in a semicircle with the diameter as hypotenuse has a right angle |
| **Square Areas** | The area of the square on each side equals the side length squared |

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — all rendering done via the Canvas 2D API
- **Vanilla JavaScript** — no external libraries or frameworks
- **CSS3** — responsive layout with Google Fonts (DM Sans, JetBrains Mono, Crimson Pro)
- **Touch Events** — full mobile/tablet support
- **SVG** — used in step-by-step Pythagorean proof panels

---

## 💡 How to Use

1. **Click and drag** the highlighted points to change angles interactively
2. Watch the **angle values** and **interior sum** update in real time
3. In Demo 1, drag any corner to resize the rectangle — all angles stay at 90°
4. In Demo 4, use **Step 1–5 buttons** to walk through the Pythagorean proof
5. In Demo 5, drag point **B left/right** along the baseline to change the triangle
6. In Demo 6 & 7, drag point **C anywhere around the full circle** to explore all quadrants

---

## 📂 Project Structure

```
week06/
├── README.md
├── rectangle_angles.html           ← Demo 1: Rectangle with 4 right angles
├── triangle_interior_angles.html   ← Demo 2: Draggable triangle
├── right_angles.html               ← Demo 3: Right triangle on circle
├── Pythagorean.html                ← Demo 4: Step-by-step Pythagorean proof
├── angle_Pythagorean-1.html        ← Demo 5: Dynamic triangle, drag along baseline
├── angle_Pythagorean-2.html        ← Demo 6: Circle radius 5, fixed left end I
└── angle_Pythagorean-3.html        ← Demo 7: Circle radius 5, hypotenuse from center
```

---

## 📄 License

This project is for educational purposes. Feel free to use and modify.
