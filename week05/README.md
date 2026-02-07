# Week 05 - Interactive Circle Angle Visualizations

This repository contains three progressive HTML visualizations demonstrating circle geometry, angles, radians, and arc length calculations. Each file builds upon the previous one with enhanced features.

## 🚀 Live Demos

[![Open Demo 1](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Basic%20Angle-3498db?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/circle_angle_v1.html)

[![Open Demo 2](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Enhanced%20with%20Buttons-e67e22?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/circle_angle_v2.html)

[![Open Demo 3](https://img.shields.io/badge/▶%20Open%20Live%20Demo-Complete%20with%20Radians-9b59b6?style=for-the-badge&logo=github)](https://benchvue.github.io/GeoGebra/week05/circle_angle_v3.html)

## 📁 Files

1. **`circle_angle_v1.html`** - Basic Interactive Angle Visualization
2. **`circle_angle_v2.html`** - Enhanced with Fundamental Angles and Increment Buttons
3. **`circle_angle_v3.html`** - Complete with Radian Labels and Arc Length Display

## 🎯 Features Overview

### Version 1: Basic Interactive Angle
- Interactive draggable endpoint
- Real-time angle display in degrees
- Visual angle arc representation
- Clean, simple interface

### Version 2: Enhanced Visualization
- ✨ Fundamental angle markers (0°, 30°, 45°, 60°, 90°, etc.)
- 🔵 Four increment buttons: +30°, +45°, +60°, +90°
- 🎬 Smooth animations when using buttons
- 🎨 Better visual feedback and styling

### Version 3: Complete Mathematical Visualization
- 🔴 **Radian labels** outside the circle (π/6, π/4, π/3, etc.)
- 🟠 **Arc length display** on the circle perimeter
- 📊 **Dual angle system**: Degree and Radian angles
- 🧮 **Mathematical formula**: Shows radian = arc length / radius
- 🎯 **Reset button** to return to 0°
- 📐 Comprehensive labeling with color-coded elements

## 🎨 Color Coding (Version 3)

- **Blue** - Degree angles and radius
- **Red** - Radian angles and labels
- **Orange** - Arc length
- **Green** - Base line (starting position)
- **Gray** - Reference lines for fundamental angles

## 🚀 How to Use

### Basic Interaction
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

### Fundamental Angles
The visualization shows key angles commonly used in mathematics:
- **0° (0)** - Starting position
- **30° (π/6)** - 
- **45° (π/4)** - 
- **60° (π/3)** - 
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

## 📄 License

Free to use for educational purposes.

## 👤 Author

Created as part of Week 05 geometry studies.

---

**Note**: These are standalone HTML files with no external dependencies. Simply open them in a browser to start exploring!
