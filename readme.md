# Dynamic Archimedean Spiral Loader

This is a dynamic Archimedean spiral loader implemented using HTML5 Canvas and JavaScript for fuga technologies by dafom. The loader features multiple overlapping spirals with varying colors, providing an engaging visual effect. The script dynamically adjusts to window resizing for a responsive display.

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Parameters](#parameters)
- [Customization](#customization)
- [License](#license)

## Overview

The HTML file creates a canvas and uses JavaScript to draw an animated Archimedean spiral loader. The spirals are drawn with varying colors and border circles, creating an intricate and visually appealing effect. The animation continuously rotates the spirals, providing a dynamic and engaging display.

## Usage

To use this Archimedean spiral loader, simply open the HTML file in a web browser. The loader will automatically start, and you can observe the animated spirals. Resize the window to see the responsive behavior of the loader.

## Parameters

The loader has several parameters that can be adjusted to customize its appearance and behavior:

- `numTurns`: Number of turns in the spiral.
- `angleIncrement`: Angle increment for each point in the spiral.
- `rotationSpeed`: Speed of rotation for the spirals.
- `clockwise`: Boolean indicating the direction of rotation (clockwise or anticlockwise).
- `circleRadiusMultiplier`: Multiplier for calculating circle radius.
- `borderCircleSpacing`: Spacing between border circles.

## Customization

You can customize the loader by adjusting the parameters mentioned above. Additionally, you can change the colors of individual spirals by modifying the `lineColor` parameter in the `drawArchimedeanSpiral` function.

```javascript
drawArchimedeanSpiral(xOffset, yOffset, lineColor);
```

## Github

you can clone the project from

```

https://github.com/Dafomchollom/spiral_loader.git
```
