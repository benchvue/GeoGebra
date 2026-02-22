# GeoGebra Function Visualizations — f(x) = x²

Interactive math function animations designed to help students understand how functions transform inputs into outputs. Each visualization builds on the previous one, progressively adding more visual context to deepen understanding of the **squaring function f(x) = x²**.

---

## 📺 Live Demos

> **Click any preview below to open the live interactive animation.**

---

### 1. Function Machine + Side Length & Area Calculation

> Interactive calculator: drag a slider to select a side length (1–5 inches), and toggle to reveal the computed square area. Input is shown as a green line; output is shown as a blue square.

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Side%20Length%20%26%20Area%20Calc-27ae60?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/calculate-square.html)

```
  ┌───┐       ┌──────────────────────┐       ┌───┐
  │ 3 │  ───► │ f(x) = x²            │  ───► │ ? │
  └───┘       │ Calculate Square Area│       └───┘
  Input       └──────────────────────┘       Output

   │                                 ┌───────────┐
   │  3 in                           │           │
   │  (slider)                       │   9 in²   │  3 in
   │                                 │  (toggle) │
                                     └───────────┘
  Side Length              →              Area
```

**Features:**
- **Slider** to select integer side length: 1, 2, 3, 4, or 5 inches (no decimals)
- **Green vertical line** — height equals the selected side length in inches
- **Show/Hide Area toggle button** — output defaults to `?`; click to reveal the blue square and area value
- **Blue square** grows to match the selected side length with dimension labels (`x in` on right and bottom edges)
- Area label displayed in white at the center (e.g., `9 in²`)
- Input and output circles update live as the slider moves

---

### 2. Function Machine — Original Animation

> Basic function machine visualization: input flows through f(x) = x², output appears with step-by-step calculation.

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Function%20Machine-27ae60?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/basic-diagram.html)

```
  ┌───┐       ┌────────────┐       ┌───┐
  │ 3 │  ───► │ f(x) = x²  │  ───► │ 9 │
  └───┘       │  3² = 3×3  │       └───┘
  Input       │    = 9     │       Output
              └────────────┘
```

**Features:**
- Animated ball travels from **Input → Function Box → Output**
- Step-by-step calculation display inside the function box (e.g., `f(3) → 3² → 3 × 3 → = 9`)
- Color-coded balls: 🟢 green (input), 🟠 orange (processing), 🔵 blue (output)
- Play / Pause / Stop controls
- Loops through inputs 1 through 5

---

### 3. Function Machine + Side Length & Area Drawing

> Enhanced version with geometric visuals: a **green vertical line** shows the input as a side length (in inches), and a **blue square** shows the output as an area (in square inches).

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Side%20Length%20%26%20Area-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/square-drawing.html)

```
  ┌───┐       ┌────────────┐       ┌───┐
  │ 3 │  ───► │ f(x) = x²  │  ───► │ 9 │
  └───┘       └────────────┘       └───┘

   │                                 ┌───────────┐
   │  3 in                           │           │
   │                                 │   9 in²   │  3 in
   │                                 │           │
                                     └───────────┘
  Side Length         →                   Area
```

**Features:**
- Everything from Version 2, plus:
- **Green vertical line** — height equals the input value in inches (1 in = 48px)
- **Blue square** — side length equals input, area label displayed in white at the center (e.g., `9 in²`)
- Dimension labels on the right and bottom edges of the square (e.g., `3 in`)
- **Fixed-size containers** — visual panels are pre-reserved for the maximum case (5 in line, 5×5 in square), so nothing shifts or jumps during animation
- Green line appears when input enters; blue square grows when output is calculated

---

### 4. Function Machine + Geometry + X-Y Coordinate Plane

> Full visualization with coordinate graphing: after each step, the (x, y) point is plotted on a coordinate plane, building the **y = x² parabola** point by point.

[![Open Demo 4](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Coordinate%20Plane-9b59b6?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/squre-x-y-drawing.html)

```
  ┌───┐       ┌────────────┐       ┌───┐
  │ 3 │  ───► │ f(x) = x²  │  ───► │ 9 │
  └───┘       └────────────┘       └───┘

                                     y
   │           ┌─────────┐          │      E(5,25)
   │           │         │          │    D(4,16)
   │  3 in     │  9 in²  │ 3 in     │   C(3,9)
   │           │         │          │  B(2,4)
               └─────────┘          │ A(1,1)
  Side          Area         →      └──────────── x
  Length                            Coordinate Plane
```

**Features:**
- Everything from Versions 2 & 3, plus:
- **X-Y Coordinate Plane** with labeled axes and grid
- Points plotted one by one: **(1,1) → (2,4) → (3,9) → (4,16) → (5,25)**
- Each point labeled A through E with coordinate text (e.g., `A(1, 1)`)
- **Dashed red crosshair lines** from both axes to each point for easy reading
- **Dashed background curve** showing the full x² parabola
- **Solid blue curve** connecting plotted points, growing with each step
- Input/output circles vertically aligned with arrows
- Points list displayed below the graph
- Graph resets automatically when animation loops

---

### 5. Coefficient Explorer — x², 2x², ½x² (the "a" in ax²)

> Explore how the leading coefficient **a** affects the parabola's shape and area. Switch between three functions to see narrow, normal, and wide parabolas with visual area comparisons.

[![Open Demo 5](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Coefficient%20Explorer-e74c3c?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/quadratic-a.html)

```
         ┌──────┐   ┌──────┐   ┌──────┐
         │  x²  │   │ 2x²  │   │ ½x²  │
         │ a=1  │   │ a=2  │   │ a=½  │
         └──────┘   └──────┘   └──────┘

  ┌───┐       ┌────────────┐       ┌────┐
  │ 3 │  ───► │ f(x) = 2x² │  ───► │ 18 │
  └───┘       └────────────┘       └────┘

                  ┌─────────┐         y
   │              │ x²=9    │        │ ╱ 2x²
   │              ├─────────│        │╱   x²
   │  3 units     │ 2x²=18  │        ╱  ╱
   │              │ (2 layers)       ╱ ╱  ½x²
                  └─────────┘       └──────── x
  Side            Area (stacked)    All 3 curves
```

**Features:**
- Everything from Versions 2–4, plus:
- **Three function buttons**: `x²` (a=1), `2x²` (a=2), `½x²` (a=½) — color-coded red, purple, green
- **Coefficient comparison for area visualization**:
  - **x²** — standard square (baseline reference)
  - **2x²** — double-height rectangle with dashed midline showing two stacked layers over the x² reference outline
  - **½x²** — full x² square with only bottom half solid; top half uses a **dot pattern** to show the missing 50%
- **All three reference parabolas** drawn as dashed curves on the coordinate plane for shape comparison
- Solid curve drawn in the selected function's color as points are plotted
- **Info bar** explains the current coefficient's effect on slope and area
- Function selector disabled during playback to prevent conflicts
- Graph legend identifies all three curves

---

### 6. Y-Intercept Explorer — x², x²+5, x²−5 (the "c" in x²+c)

> Explore how the constant term **c** shifts the parabola up or down. Switch between three functions to see the vertical shift effect on the y-intercept and area visualization. A large shift of ±5 makes the difference dramatically visible.

[![Open Demo 6](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Y--Intercept%20Explorer-16a085?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/quadratic-c.html)

```
         ┌──────┐   ┌───────┐   ┌───────┐
         │  x²  │   │ x²+5  │   │ x²−5  │
         │ c=0  │   │ c=+5  │   │ c=−5  │
         └──────┘   └───────┘   └───────┘

  ┌───┐       ┌──────────────┐       ┌────┐
  │ 3 │  ───► │ f(x) = x²+5  │  ───► │ 14 │
  └───┘       └──────────────┘       └────┘

                  ┌─────────┐         y
   │              │░░ +5 ░░░│        │    x²+5
   │              │░░░░░░░░░│        │   x²
   │  3 units     │  x²=9   │        │  x²−5
   │              │         │        ● (0,5)
                  └─────────┘       ●└(0,0)──── x
  Side            Area + strip      ● (0,−5)
```

**Features:**
- Everything from Versions 2–4, plus:
- **Three function buttons**: `x²` (c=0), `x²+5` (c=+5), `x²−5` (c=−5) — color-coded red, teal, orange
- **Y-intercept shift visualized in the area panel**:
  - **x²** — standard square (baseline reference)
  - **x²+5** — x² square with a **striped band on top** showing the +5 added area (5 units tall, clearly visible)
  - **x²−5** — x² square with a **hatched band at the bottom** showing the −5 removed area (5 units tall, clearly visible)
- **4-line calculation board** showing the extra step: `f(3) = 3² + 5 → 3 × 3 + 5 → 9 + 5 → 14`
- **All three reference parabolas** drawn as dashed curves, clearly showing the large vertical offset
- **Y-intercept markers** at (0, 0), (0, 5), and (0, −5) on the coordinate plane
- Graph y-axis range extended to show full shift — from −8 up to 35
- Solid curve drawn in the selected function's color as points are plotted
- **Info bar** explains the current c value's effect on vertex position and y-intercept
- Function selector disabled during playback to prevent conflicts
- Graph legend identifies all three curves

---

### 7. Quadratic Explorer — f(x) = m(x − a)² + b (vertex form with sliders)

> Full vertex-form explorer: **three real-time sliders** control the shape and position of the parabola, showing how each parameter independently affects the curve, the vertex, and its projections onto the axes.

[![Open Demo 7](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Quadratic%20Explorer-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week04/function-quadratic.html)

```
         ┌──────────────┐   ┌──────────────┐   ┌──────────────┐
         │    m = 2     │   │    a = 1     │   │    b = 1     │
         │  narrowness  │   │  x-offset    │   │  y-offset    │
         └──────────────┘   └──────────────┘   └──────────────┘
                    ◄────────────── sliders ──────────────►

                              y
                              │        ╭─╮
                              │       ╱   ╲
                  B (0, b) ●──┼──────╱─────╲────
                    (red)  │  │     ╱   O(a,b)
                              │    ╱    ● (green)
                              │   ╱
                              │  ╱
                              ──┼──────●──────────── x
                                │    A(a,0)
                                │    (blue)

         f(x) = m(x − a)² + b       vertex form
```

**Features:**
- **Interactive sliders** for all three vertex-form parameters, updated in real time:
  - **m** (narrowness) — stretches or compresses the parabola; positive opens upward, negative opens downward
  - **a** (x-offset) — shifts the vertex left and right along the x-axis
  - **b** (y-offset) — shifts the vertex up and down along the y-axis
- **Three labeled key points** that move live with the sliders:
  - 🟢 **O (a, b)** — the vertex of the parabola (dark green)
  - 🔵 **A (a, 0)** — projection of the vertex onto the x-axis (blue)
  - 🔴 **B (0, b)** — projection of the vertex onto the y-axis (red)
- **Dashed helper lines** connecting the vertex to both axis projections for easy reading
- **White background coordinate plane** with black grid lines, tick marks, and axis labels
- **Dark green parabola** redrawn instantly as sliders change
- No animation loop — fully manual, student-driven exploration

---

## 🧠 How It Works

Each animation demonstrates the same core concept in increasing detail:

```
Input (x)  →  f(x) = x²  →  Output (y = x²)
```

| Step | Input (x) | Calculation | Output (y) | Point on Graph |
|------|-----------|-------------|------------|----------------|
| 1    | 1         | 1² = 1 × 1 | 1          | (1, 1)         |
| 2    | 2         | 2² = 2 × 2 | 4          | (2, 4)         |
| 3    | 3         | 3² = 3 × 3 | 9          | (3, 9)         |
| 4    | 4         | 4² = 4 × 4 | 16         | (4, 16)        |
| 5    | 5         | 5² = 5 × 5 | 25         | (5, 25)        |

### Version 5 — Coefficient Comparison Table (a)

| Step | Input (x) | x² (a=1) | 2x² (a=2) | ½x² (a=½) |
|------|-----------|----------|------------|------------|
| 1    | 1         | 1        | 2          | 0.5        |
| 2    | 2         | 4        | 8          | 2          |
| 3    | 3         | 9        | 18         | 4.5        |
| 4    | 4         | 16       | 32         | 8          |
| 5    | 5         | 25       | 50         | 12.5       |

### Version 6 — Y-Intercept Comparison Table (c)

| Step | Input (x) | x² (c=0) | x²+5 (c=+5) | x²−5 (c=−5) |
|------|-----------|----------|--------------|--------------|
| 1    | 1         | 1        | 6            | −4           |
| 2    | 2         | 4        | 9            | −1           |
| 3    | 3         | 9        | 14           | 4            |
| 4    | 4         | 16       | 21           | 11           |
| 5    | 5         | 25       | 30           | 20           |

### Version 7 — Vertex Form Parameter Effects (m, a, b)

| Parameter | Default | Effect on Parabola                                      |
|-----------|---------|---------------------------------------------------------|
| m         | 2       | Larger \|m\| → narrower; smaller \|m\| → wider; m < 0 → flips downward |
| a         | 1       | Shifts vertex (and curve) left (−) or right (+) along x-axis |
| b         | 1       | Shifts vertex (and curve) down (−) or up (+) along y-axis   |

### Visual Progression Across Versions

```
Version 1:  ◄── Slider (1–5) ──►  [ Show/Hide Area Toggle ]
            [ Input ] ──► [ Function Box ] ──► [ Output (? / revealed) ]
            │ Green Line │       →        │ Blue Square (on toggle) │

Version 2:  [ Input ] ──► [ Function Box ] ──► [ Output ]

Version 3:  [ Input ] ──► [ Function Box ] ──► [ Output ]
            │ Green Line │       →        │ Blue Square │

Version 4:  [ Input ] ──► [ Function Box ] ──► [ Output ]
            │ Green Line │  →  │ Blue Square │  →  │ X-Y Graph │

Version 5:  [ x² ] [ 2x² ] [ ½x² ]  ← "a" Selector (narrow / wide)
            [ Input ] ──► [ Function Box ] ──► [ Output ]
            │ Green Line │  →  │ Area (with overlays) │  →  │ X-Y Graph (3 curves) │

Version 6:  [ x² ] [ x²+5 ] [ x²−5 ]  ← "c" Selector (shift up / down)
            [ Input ] ──► [ Function Box ] ──► [ Output ]
            │ Green Line │  →  │ Area (with ±5 strip) │  →  │ X-Y Graph (3 curves) │

Version 7:  ◄── m slider ──►  ◄── a slider ──►  ◄── b slider ──►
            │ Live coordinate plane │ → │ O(a,b) vertex │ → │ A(a,0) + B(0,b) projections │
```

---

## 🎮 Controls

Versions 2–4 share the same controls:

| Button    | Action                                            |
|-----------|---------------------------------------------------|
| ▶ **Play**  | Start or resume the animation                   |
| ⏸ **Pause** | Pause after current phase completes              |
| ⏹ **Stop**  | Reset everything — animation, values, and graph  |

Version 1 adds:

| Control           | Action                                                    |
|-------------------|-----------------------------------------------------------|
| **Slider (1–5)**  | Select integer side length (1, 2, 3, 4, or 5 inches)    |
| **Show Area**     | Reveal the blue square and computed area value           |
| **Hide Area**     | Hide the output square, reset output circle to `?`       |

Version 5 adds:

| Button       | Action                                         |
|--------------|------------------------------------------------|
| **x²**       | Select normal parabola (a = 1)                |
| **2x²**      | Select narrow/steep parabola (a = 2)          |
| **½x²**      | Select wide/flat parabola (a = ½)             |

Version 6 adds:

| Button       | Action                                           |
|--------------|--------------------------------------------------|
| **x²**       | Select base parabola (c = 0, vertex at origin)  |
| **x²+5**     | Select shifted-up parabola (c = +5)             |
| **x²−5**     | Select shifted-down parabola (c = −5)           |

Version 7 adds:

| Control      | Action                                                   |
|--------------|----------------------------------------------------------|
| **m slider** | Drag to change narrowness / direction (range: −5 to 5)  |
| **a slider** | Drag to shift the vertex left or right (range: −4 to 4) |
| **b slider** | Drag to shift the vertex up or down (range: −4 to 4)    |

---

## 📁 File Structure

```
week04/
├── calculate-square.html       # Version 1: Slider + Show/Hide Area toggle
├── basic-diagram.html          # Version 2: Basic function machine
├── square-drawing.html         # Version 3: + Side length & area visuals
├── squre-x-y-drawing.html      # Version 4: + Coordinate plane graphing
├── quadratic-a.html            # Version 5: + Coefficient explorer (x², 2x², ½x²)
├── quadratic-c.html            # Version 6: + Y-intercept explorer (x², x²+5, x²−5)
├── function-quadratic.html     # Version 7: + Quadratic explorer f(x) = m(x−a)²+b
└── readme.md                   # This file
```

---

## 🚀 Usage

### View Online (GitHub Pages)

Simply click any of the **Open Live Demo** buttons above — no installation required.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/benchvue/GeoGebra.git
   ```
2. Open any HTML file directly in your browser:
   ```bash
   open GeoGebra/week04/calculate-square.html
   ```

No build tools, dependencies, or server required — each file is a self-contained HTML page with embedded CSS and JavaScript.

---

## 🎓 Educational Context

These visualizations support teaching **function concepts** in algebra and pre-calculus:

- **Function as a machine** — input goes in, rule is applied, output comes out
- **Function notation** — understanding f(x), substitution, evaluation
- **Squaring function** — non-linear growth, squared values increase rapidly
- **Geometric interpretation** — side length vs. area of a square
- **Coordinate graphing** — plotting ordered pairs (x, y) to form a curve
- **Parabola shape** — seeing how y = x² creates the classic U-shaped curve
- **Effect of coefficients** — how the leading coefficient *a* stretches or compresses the parabola and scales the output area (Version 5)
- **Vertical shifts** — how the constant *c* moves the parabola up or down, changing the y-intercept without changing the shape; using ±5 makes the shift dramatically visible compared to the curve (Version 6)
- **Vertex form** — how m, a, and b in f(x) = m(x − a)² + b each independently control the shape, horizontal position, and vertical position of the parabola (Version 7)

---

## 📝 Technical Notes

- All animations are pure **HTML / CSS / JavaScript** with no external dependencies
- Canvas API is used for the coordinate plane graph (Versions 4, 5, 6 & 7)
- CSS transitions and `setTimeout` for animation sequencing
- Responsive design works on desktop and tablet browsers
- Each HTML file is fully self-contained (single file, no build step)

---

## 📄 License

MIT — free to use, modify, and share for educational purposes.
