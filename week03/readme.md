# GeoGebra Function Visualizations — Linear Functions

Interactive math function animations to help students understand how **linear functions** work. Each visualization builds on the previous one, progressively adding more visual context.

---

## 📺 Live Demos

> **Click any preview below to open the live interactive animation.**

---

### 1. Function Machine — Basic Animation (Horizontal)

> Input flows left-to-right through f(x) = 2x + 1, output appears with step-by-step calculation.

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Function%20Machine-27ae60?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week03/function-2x+1.html)

```
  ┌───┐       ┌──────────────┐       ┌───┐
  │ 3 │  ───► │ f(x) = 2x+1  │  ───► │ 7 │
  └───┘       │  2×3 + 1      │       └───┘
  Input       │    = 7        │       Output
              └──────────────┘
```

**Features:**
- Animated ball travels from **Input → Function Box → Output**
- Step-by-step calculation display
- Color-coded balls: 🟢 green (input), 🟠 orange (processing), 🔵 blue (output)
- Play / Pause / Stop controls
- Loops through inputs 0, 1, 2, 3

---

### 2. Function Machine — Vertical Layout with X-Y Graph

> Vertical function machine paired with an x-y coordinate graph that plots each point as it's calculated.

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Vertical%20%2B%20Graph-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week03/function-stacking.html)

```
        ┌───┐                        y
        │ 7 │ Output (y)             │    D(3,7)
        └───┘                        │   C(2,5)
          ▲                          │  B(1,3)
    ┌──────────────┐                 │ A(0,1)
    │ f(x) = 2x+1  │                 └──────────── x
    │  f(3) = 2×3+1│
    │  f(3) = 6+1  │
    │  f(3) = 7    │
    └──────────────┘
          ▲
        ┌───┐
        │ 3 │ Input (x)
        └───┘
```

**Features:**
- Vertical flow — input enters from the bottom, output exits from the top
- Multi-line calculation board showing step-by-step work
- X-Y Coordinate Plane with points plotted one by one: **(0,1) → (1,3) → (2,5) → (3,7)**
- Each point labeled A through D
- Dashed connecting line between plotted points

---

### 3. Function Machine — Horizontal with X-Y Graph

> Horizontal function machine combined with a coordinate plane side-by-side.

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Horizontal%20%2B%20Graph-9b59b6?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week03/function-x-y-drawing.html)

```
  ┌───┐       ┌──────────────┐       ┌───┐
  │ 3 │  ───► │ f(x) = 2x+1  │  ───► │ 7 │
  └───┘       └──────────────┘       └───┘

                    y
                    │    D(3,7)
                    │   C(2,5)
                    │  B(1,3)
                    │ A(0,1)
                    └──────────── x
```

**Features:**
- Horizontal left-to-right function machine
- X-Y Coordinate Plane plotting all calculated points
- Dashed connecting line showing the linear pattern
- Points accumulate: **(0,1) → (1,3) → (2,5) → (3,7)**

---

### 4. Interactive Slider — f(x) = mx + b

> Adjust slope m and y-intercept b with sliders. See the line update live on the coordinate plane.

[![Open Demo 4](https://img.shields.io/badge/▶%20Open%20Live%20Demo-f(x)%20%3D%20mx%20%2B%20b-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week03/function-mx+b.html)

```
  f(x) = 2x + 0

  ──────●────────  m = 2  (slope)
  ──────●────────  b = 0  (y-intercept)

         y          ╱
         │         ╱
         │        ╱
         │       ╱
         └──────────── x
```

**Features:**
- Sliders for **m** (slope) and **b** (y-intercept), range −5 to 5
- Line updates in real time as sliders move
- Red dot tracks the y-intercept point **(0, b)** on the y-axis
- Live equation display at the top

---

### 5. Interactive Slider — f(x) = m(x − a) + b

> Adjust slope m, x-shift a, and y-shift b. Visualizes the point-slope form of a linear function.

[![Open Demo 5](https://img.shields.io/badge/▶%20Open%20Live%20Demo-f(x)%20%3D%20m(x--a)%20%2B%20b-1abc9c?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week03/function-mx-a+b.html)

```
  f(x) = 2(x − 0) + 0

  ──────●────────  m = 2  (slope)
  ──────●────────  a = 0  (x-shift)
  ──────●────────  b = 0  (y-shift)

         y        ╱
         │    🟢(a,b)
         │      ╱
    🔴───┼─────╱──── x
         │🔵  ╱
```

**Features:**
- Sliders for **m**, **a**, and **b**, each ranging −5 to 5
- 🔵 Blue dot tracks **(a, 0)** on the x-axis
- 🔴 Red dot tracks **(0, b)** on the y-axis
- 🟢 Green dot marks the anchor point **(a, b)** on the line
- Right-angle triangle shows rise over run (slope m)
- Live equation display updates with correct signs

---

## 🧠 How It Works

```
Input (x)  →  f(x) = 2x + 1  →  Output (y)
```

| Step | Input (x) | Calculation    | Output (y) | Point      |
|------|-----------|----------------|------------|------------|
| 1    | 0         | 2×0 + 1 = 1   | 1          | (0, 1)     |
| 2    | 1         | 2×1 + 1 = 3   | 3          | (1, 3)     |
| 3    | 2         | 2×2 + 1 = 5   | 5          | (2, 5)     |
| 4    | 3         | 2×3 + 1 = 7   | 7          | (3, 7)     |

---

## 🎮 Controls

| Button      | Action                                      |
|-------------|---------------------------------------------|
| ▶ **Play**  | Start or resume the animation               |
| ⏸ **Pause** | Pause after current phase completes         |
| ⏹ **Stop**  | Reset everything                            |

---

## 📁 File Structure

```
week03/
├── function-2x+1.html          # Demo 1: Basic horizontal function machine
├── function-stacking.html       # Demo 2: Vertical layout + X-Y graph
├── function-x-y-drawing.html    # Demo 3: Horizontal layout + X-Y graph
├── function-mx+b.html           # Demo 4: Interactive sliders — f(x) = mx + b
├── function-mx-a+b.html         # Demo 5: Interactive sliders — f(x) = m(x−a) + b
└── readme.md                    # This file
```

---

## 🎓 Educational Context

- **Function as a machine** — input goes in, rule is applied, output comes out
- **Slope and y-intercept** — slope = rate of change, y-intercept = starting value
- **Point-slope form** — f(x) = m(x−a) + b anchors the line at a specific point
- **Coordinate graphing** — plotting ordered pairs to form a straight line
- **Comparing functions** — how m, a, and b each affect the line

---

## 📝 Technical Notes

- Pure **HTML / CSS / JavaScript** — no external dependencies
- Canvas API for coordinate plane rendering
- Each file is fully self-contained (single file, no build step)

---

## 📄 License

MIT — free to use, modify, and share for educational purposes.
