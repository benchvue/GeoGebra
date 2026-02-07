# GeoGebra Function Visualizations — f(x) = 2x + 1

Interactive math function animations designed to help students understand how **linear functions** transform inputs into outputs. Each visualization builds on the previous one, progressively adding more visual context to deepen understanding of the **linear function f(x) = 2x + 1**.

---

## 📺 Live Demos

> **Click any preview below to open the live interactive animation.**

---

### 1. Function Machine — Basic Animation (Horizontal)

> Basic function machine visualization: input flows left-to-right through f(x) = 2x + 1, output appears with step-by-step calculation.

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
- Step-by-step calculation display (e.g., `f(3) → 2×3 + 1 → = 7`)
- Color-coded balls: 🟢 green (input), 🟠 orange (processing), 🔵 blue (output)
- Play / Pause / Stop controls
- Loops through inputs 0, 1, 2, 3

---

### 2. Function Machine — Vertical Layout with X-Y Coordinate Plane

> Vertical function machine (bottom-to-top flow) paired with an x-y coordinate graph that plots each point as it's calculated.

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Vertical%20%2B%20Graph-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week03/function-stacking.html)

```
        ┌───┐                        y
        │ 7 │ Output (y)             │    D(3,7)
        └───┘                        │   C(2,5)
          ▲                          │  B(1,3)
    ┌──────────────┐                 │ A(0,1)
    │ f(x) = 2x+1  │                └──────────── x
    │  f(3) = 2×3+1 │               Coordinate Plane
    │  f(3) = 6+1   │
    │  f(3) = 7     │
    └──────────────┘
          ▲
        ┌───┐
        │ 3 │ Input (x)
        └───┘

  Function Machine              X-Y Graph
  (bottom → top)           (points accumulate)
```

**Features:**
- Everything from Version 1, plus:
- **Vertical flow** — input enters from the bottom, output exits from the top
- **Multi-line calculation board** — shows step-by-step work line by line (e.g., `f(3) = 2×3 + 1` → `f(3) = 6 + 1` → `f(3) = 7`)
- **X-Y Coordinate Plane** with labeled axes and grid
- Points plotted one by one: **(0,1) → (1,3) → (2,5) → (3,7)**
- Each point labeled A through D with coordinate text
- **Dashed connecting line** between plotted points
- Input labeled as **x-axis**, Output labeled as **y-axis**
- Points list displayed below the graph
- Graph resets automatically when animation loops

---

### 3. Function Machine — Original Horizontal with Graph

> Combines the horizontal function machine layout with the coordinate plane, providing a clean side-by-side view.

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
                   Coordinate Plane
```

**Features:**
- Horizontal left-to-right function machine
- **X-Y Coordinate Plane** plotting all calculated points
- Dashed connecting line showing the **linear pattern** (straight line)
- Points accumulate across steps: **(0,1) → (1,3) → (2,5) → (3,7)**
- Visual proof that **f(x) = 2x + 1** produces a **straight line**

---

## 🧠 How It Works

Each animation demonstrates the same core concept in increasing detail:

```
Input (x)  →  f(x) = 2x + 1  →  Output (y = 2x + 1)
```

| Step | Input (x) | Calculation       | Output (y) | Point on Graph |
|------|-----------|-------------------|------------|----------------|
| 1    | 0         | 2 × 0 + 1 = 1    | 1          | (0, 1)         |
| 2    | 1         | 2 × 1 + 1 = 3    | 3          | (1, 3)         |
| 3    | 2         | 2 × 2 + 1 = 5    | 5          | (2, 5)         |
| 4    | 3         | 2 × 3 + 1 = 7    | 7          | (3, 7)         |

### Why a Straight Line?

The function **f(x) = 2x + 1** is a **linear function**:
- **Slope (m) = 2** — output increases by 2 for every 1 increase in input
- **Y-intercept (b) = 1** — the line crosses the y-axis at (0, 1)
- All plotted points lie on a **perfectly straight line**

### Visual Progression Across Versions

```
Version 1:  [ Input ] ──► [ Function Box ] ──► [ Output ]
                          (horizontal flow)

Version 2:  [ Input ]          │
                ▲              │  [ X-Y Graph ]
            [ Function ]       │
                ▲              │
            [ Output ]         │
            (vertical flow + graph side by side)

Version 3:  [ Input ] ──► [ Function Box ] ──► [ Output ]
                          (horizontal flow)
                        [ X-Y Graph below ]
```

---

## 🎮 Controls

All three versions share the same controls:

| Button    | Action                                            |
|-----------|---------------------------------------------------|
| ▶ **Play**  | Start or resume the animation                   |
| ⏸ **Pause** | Pause after current phase completes              |
| ⏹ **Stop**  | Reset everything — animation, values, and graph  |

---

## 📁 File Structure

```
week03/
├── function-2x+1.html          # Version 1: Basic horizontal function machine
├── function-stacking.html       # Version 2: Vertical layout + X-Y graph
├── function-x-y-drawing.html    # Version 3: Horizontal layout + X-Y graph
└── readme.md                    # This file
```

---

## 🚀 Usage

### View Online (GitHub Pages)

Simply click any of the green/blue/purple **Open Live Demo** buttons above — no installation required.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/benchvue/GeoGebra.git
   ```
2. Open any HTML file directly in your browser:
   ```bash
   open GeoGebra/week03/function-2x+1.html
   ```

No build tools, dependencies, or server required — each file is a self-contained HTML page with embedded CSS and JavaScript.

---

## 🎓 Educational Context

These visualizations support teaching **linear function concepts** in algebra:

- **Function as a machine** — input goes in, rule is applied, output comes out
- **Function notation** — understanding f(x), substitution, evaluation
- **Linear function** — constant rate of change, produces a straight line
- **Slope and y-intercept** — slope = 2 (rise over run), y-intercept = 1
- **Coordinate graphing** — plotting ordered pairs (x, y) to form a line
- **Pattern recognition** — output increases by 2 for every input increase of 1

---

## 🔗 Related

- **[Week 04 — f(x) = x²](../week04/readme.md)** — Quadratic function with side length, area drawing, and parabola graphing

---

## 📝 Technical Notes

- All animations are pure **HTML / CSS / JavaScript** with no external dependencies
- Canvas API is used for the coordinate plane graph
- CSS transitions and `setTimeout` for animation sequencing
- Responsive design works on desktop and tablet browsers
- Each HTML file is fully self-contained (single file, no build step)

---

## 📄 License

MIT — free to use, modify, and share for educational purposes.
