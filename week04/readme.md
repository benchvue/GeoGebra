# GeoGebra Function Visualizations — f(x) = x²

Interactive math function animations designed to help students understand how functions transform inputs into outputs. Each visualization builds on the previous one, progressively adding more visual context to deepen understanding of the **squaring function f(x) = x²**.

---

## 📺 Live Demos

### 1. Function Machine — Original Animation

> Basic function machine visualization: input flows through f(x) = x², output appears with step-by-step calculation.

🔗 **[Open Full Page](https://benchvue.github.io/GeoGebra/week04/basic-diagram.html)**

<iframe src="https://benchvue.github.io/GeoGebra/week04/basic-diagram.html" width="100%" height="500" style="border:2px solid #ddd; border-radius:12px;" allowfullscreen></iframe>

**Features:**
- Animated ball travels from **Input → Function Box → Output**
- Step-by-step calculation display inside the function box (e.g., `f(3) → 3² → 3 × 3 → = 9`)
- Color-coded balls: 🟢 green (input), 🟠 orange (processing), 🔵 blue (output)
- Play / Pause / Stop controls
- Loops through inputs 1 through 5

---

### 2. Function Machine + Side Length & Area Drawing

> Enhanced version with geometric visuals: a **green vertical line** shows the input as a side length (in inches), and a **blue square** shows the output as an area (in square inches).

🔗 **[Open Full Page](https://benchvue.github.io/GeoGebra/week04/square-drawing.html)**

<iframe src="https://benchvue.github.io/GeoGebra/week04/square-drawing.html" width="100%" height="750" style="border:2px solid #ddd; border-radius:12px;" allowfullscreen></iframe>

**Features:**
- Everything from Version 1, plus:
- **Green vertical line** — height equals the input value in inches (1 in = 48px)
- **Blue square** — side length equals input, area label displayed in white at the center (e.g., `9 in²`)
- Dimension labels on the right and bottom edges of the square (e.g., `3 in`)
- **Fixed-size containers** — visual panels are pre-reserved for the maximum case (5 in line, 5×5 in square), so nothing shifts or jumps during animation
- Green line appears when input enters; blue square grows when output is calculated

---

### 3. Function Machine + Geometry + X-Y Coordinate Plane

> Full visualization with coordinate graphing: after each step, the (x, y) point is plotted on a coordinate plane, building the **y = x² parabola** point by point.

🔗 **[Open Full Page](https://benchvue.github.io/GeoGebra/week04/squre-x-y-drawing.html)**

<iframe src="https://benchvue.github.io/GeoGebra/week04/squre-x-y-drawing.html" width="100%" height="800" style="border:2px solid #ddd; border-radius:12px;" allowfullscreen></iframe>

**Features:**
- Everything from Versions 1 & 2, plus:
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

### Visual Progression

```
Version 1:  [Input] → [Function Box] → [Output]

Version 2:  [Input] → [Function Box] → [Output]
             |  Green Line  |  →  |  Blue Square  |

Version 3:  [Input] → [Function Box] → [Output]
             |  Green Line  |  →  |  Blue Square  |  →  | X-Y Graph |
```

---

## 🎮 Controls

All three versions share the same controls:

| Button   | Action                                           |
|----------|--------------------------------------------------|
| **Play** | Start or resume the animation                    |
| **Pause**| Pause after current phase completes               |
| **Stop** | Reset everything — animation, values, and graph   |

---

## 📁 File Structure

```
week04/
├── basic-diagram.html         # Version 1: Basic function machine
├── square-drawing.html      # Version 2: + Side length & area visuals
├── squre-x-y-drawing.html   # Version 3: + Coordinate plane graphing
└── README.md                   # This file
```

---

## 🚀 Usage

### View Online (GitHub Pages)

Simply visit any of the live demo links above — no installation required.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/benchvue/GeoGebra.git
   ```
2. Open any HTML file directly in your browser:
   ```bash
   open GeoGebra/week04/basic-diagram.html
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

---

## 📝 Notes

- All animations are pure HTML/CSS/JavaScript with **no external dependencies**
- Canvas API is used for the coordinate plane graph
- Responsive design works on desktop and tablet browsers
- Animations use CSS transitions and `setTimeout` for sequencing
- The `iframe` previews above render on GitHub Pages but **not** in the GitHub repository README viewer (GitHub strips iframes for security). Use the "Open Full Page" links instead if viewing from GitHub directly.

---

## 📄 License

MIT — free to use, modify, and share for educational purposes.
