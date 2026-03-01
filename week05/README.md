# Week 05 - Interactive Circle Angle Visualizations

This repository contains three progressive HTML visualizations demonstrating circle geometry, angles, radians, and arc length calculations, plus three interactive angle quizzes for learning internal angles of shapes.

## 🚀 Live Demos

### 🧩 Angle Quizzes

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Square%20Angle%20Quiz-10b981?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/square-angle-quiz.html)

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Triangle%20Angle%20Quiz-10b981?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/triangle-angle-quiz.html)

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Equilateral%20Triangle%20Quiz-10b981?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/equilateral-triangle-quiz.html)

### 🔵 Circle Angle Visualizations

[![Open Demo 4](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Basic%20Angle-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/circle_angle_v1.html)

[![Open Demo 5](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Enhanced%20with%20Buttons-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/circle_angle_v2.html)

[![Open Demo 6](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Complete%20with%20Radians-9b59b6?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/circle_angle_v3.html)

## 📁 Files

1. **`square-angle-quiz.html`** - Square Internal Angle Quiz
2. **`triangle-angle-quiz.html`** - Isosceles Right Triangle Angle Quiz
3. **`equilateral-triangle-quiz.html`** - Equilateral Triangle Angle Quiz
4. **`circle_angle_v1.html`** - Basic Interactive Angle Visualization
5. **`circle_angle_v2.html`** - Enhanced with Fundamental Angles and Increment Buttons
6. **`circle_angle_v3.html`** - Complete with Radian Labels and Arc Length Display

## 🧩 Angle Quiz Features

### Demo 1: Square Angle Quiz (`square-angle-quiz.html`)
- 📐 Shows a square with **?** at each of the four corners
- 🟢 Green right-angle indicators at every corner
- ✅ **Show Answer** reveals `90°` at all four corners
- 🔢 Animated angle sum card: `90° + 90° + 90° + 90° = 360°`
- 💡 Chips pop in one by one to build the equation

### Demo 2: Isosceles Right Triangle Quiz (`triangle-angle-quiz.html`)
- 📐 Square cut diagonally — shows the resulting isosceles right triangle
- 🔲 Dashed ghost square (top & right edges) shows the original shape
- 🟢 Right angle (90°) always shown; two **?** marks at the 45° corners
- ✅ **Show Answer** reveals both corners as `45°`
- 💡 Includes equation: `90° + 45° + 45° = 180°`

### Demo 3: Equilateral Triangle Quiz (`equilateral-triangle-quiz.html`)
- 📐 Equilateral triangle constructed from two overlapping circles
- 🔵 Blue vertex dots and double tick marks on all three equal sides
- 🟢 Three **?** marks inside, one at each corner
- ✅ **Show Answer** reveals all three angles as `60°`
- 🔢 Animated angle sum card: `60° + 60° + 60° = 180°`
- 💡 Reinforces: every triangle's angles sum to 180°

## 🎯 Circle Visualization Features Overview

### Demo 4: Basic Interactive Angle (`circle_angle_v1.html`)
- Interactive draggable endpoint
- Real-time angle display in degrees
- Visual angle arc representation
- Clean, simple interface

### Demo 5: Enhanced Visualization (`circle_angle_v2.html`)
- ✨ Fundamental angle markers (0°, 30°, 45°, 60°, 90°, etc.)
- 🔵 Four increment buttons: +30°, +45°, +60°, +90°
- 🎬 Smooth animations when using buttons
- 🎨 Better visual feedback and styling

### Demo 6: Complete Mathematical Visualization (`circle_angle_v3.html`)
- 🔴 **Radian labels** outside the circle (π/6, π/4, π/3, etc.)
- 🟠 **Arc length display** on the circle perimeter
- 📊 **Dual angle system**: Degree and Radian angles
- 🧮 **Mathematical formula**: Shows radian = arc length / radius
- 🎯 **Reset button** to return to 0°
- 📐 Comprehensive labeling with color-coded elements

## 🎨 Color Coding

### Angle Quizzes (Demos 1–3)
- **Blue** (`#2563eb`) — Shape borders and tick marks
- **Green** (`#10b981`) — Angle arcs, labels, and right-angle indicators
- **Light Blue** — Shape fill

### Circle Visualizations (Demos 4–6)
- **Blue** — Degree angles and radius
- **Red** — Radian angles and labels
- **Orange** — Arc length
- **Green** — Base line (starting position)
- **Gray** — Reference lines for fundamental angles

## 🚀 How to Use

### Angle Quizzes (Demos 1–3)
1. **Study the shape** and try to figure out each **?** angle
2. **Click "Show Answer"** to reveal all angles and the animated sum equation
3. **Click "Try Again"** to reset and quiz yourself again

### Circle Visualizations (Demos 4–6)
1. **Drag the endpoint**: Click and drag the blue endpoint around the circle to change the angle
2. **Use increment buttons**: Click +30°, +45°, +60°, or +90° to automatically rotate
3. **Reset to zero**: Click the "Reset to 0°" button to return to starting position

### Understanding the Display

#### Degree Angle (Blue)
Shows the angle in degrees from 0° to 360°

#### Radian Angle (Red)
Shows the same angle in radians with the formula:
```
Radian = Arc Length / Radius
```

Since radius = 1 in this visualization:
```
Radian = Arc Length
```

#### Arc Length (Orange)
The distance along the circle's perimeter from the start point to the endpoint

## 📐 Mathematical Concepts

### Internal Angle Sums
| Shape | Each Angle | Sum of All Angles |
|-------|-----------|-------------------|
| Equilateral Triangle | 60° | 180° |
| Isosceles Right Triangle | 90°, 45°, 45° | 180° |
| Square | 90° | 360° |

### Fundamental Angles
The visualization shows key angles commonly used in mathematics:
- **0° (0)** - Starting position
- **30° (π/6)**
- **45° (π/4)**
- **60° (π/3)**
- **90° (π/2)** - Quarter circle
- **180° (π)** - Half circle
- **270° (3π/2)** - Three quarters
- **360° (2π)** - Full circle

### Radian Definition
A radian is the angle subtended at the center of a circle by an arc equal in length to the radius. The relationship is:

```
θ (radians) = Arc Length / Radius
```

For a unit circle (radius = 1):
```
θ (radians) = Arc Length
```

### Conversion Formulas
- **Degrees to Radians**: `radians = degrees × π / 180`
- **Radians to Degrees**: `degrees = radians × 180 / π`

## 🔧 Technical Details

### Technologies Used
- Pure HTML5
- Canvas API for graphics
- Vanilla JavaScript (no external libraries)
- CSS3 for styling

### Browser Compatibility
Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (with touch support)

### Features Implementation
- **Smooth animations** using `requestAnimationFrame`
- **Easing functions** for natural motion
- **Touch support** for mobile devices
- **Responsive design** adapts to different screen sizes

## 📱 Mobile Support

All visualizations include full touch support:
- Touch and drag the endpoint
- Tap buttons to increment angles
- Pinch to zoom (browser native)

## 🎓 Educational Use

These visualizations are ideal for:
- Teaching trigonometry concepts
- Demonstrating the relationship between degrees and radians
- Visualizing arc length calculations
- Interactive mathematics education
- Self-study and exploration
- **Quizzing students on internal angles of common shapes**

## 💾 Offline Usage

To use these files offline:
1. Download the HTML file
2. Open it in any web browser
3. No internet connection required!

## 📝 Notes

- All calculations assume a unit circle (radius = 1)
- Angles are measured counterclockwise from the positive x-axis (0°)
- The visualization maintains precision to 0.1° for display purposes
- Animations take 500ms for smooth transitions

## 🤝 Contributing

Feel free to fork this repository and enhance the visualizations! Some ideas:
- Add more angle increment options
- Include trigonometric function values (sin, cos, tan)
- Add animation speed controls
- Include angle input field for direct entry
- Add multiple angle comparison mode
- Add more shape quizzes (pentagon, hexagon, etc.)

## 📄 License

Free to use for educational purposes.

## 👤 Author

Created as part of Week 05 geometry studies.

---

**Note**: These are standalone HTML files with no external dependencies. Simply open them in a browser to start exploring!
