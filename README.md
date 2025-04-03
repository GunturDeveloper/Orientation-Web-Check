# 3D Cube with Device Orientation

## Overview
This project is a simple 3D cube that reacts to device orientation using JavaScript. The cube's rotation is controlled by the device's gyroscope, providing an interactive experience that visualizes real-time orientation changes.

## Features
- **Device Orientation Support**: The cube rotates based on the gyroscope data from the device.
- **Real-Time FPS Display**: Frames per second (FPS) tracking for performance monitoring.
- **Dynamic Rotation Values**: Displays live X, Y, and Z rotation angles.
- **Simple & Lightweight**: Built using pure HTML, CSS, and JavaScript, without external libraries.

## How It Works
- The script listens to `deviceorientation` events and applies the received rotation angles (`alpha`, `beta`, `gamma`) to the cube.
- Rotation values are updated dynamically in the UI.
- FPS is calculated based on frame rendering time.

## Usage
1. Open `index.html` in a mobile browser that supports device orientation events.
2. Tilt and rotate your device to see the cube react in real time.
3. Check the displayed rotation values and FPS to monitor performance.

## Compatibility
- Works best on mobile devices with a gyroscope.
- Requires a modern browser (Chrome, Firefox, Safari, or Edge).
- If the device does not support orientation events, an alert will notify the user.

## Future Enhancements
- Improve cube rendering with WebGL for better performance.
- Customize cube colors and textures dynamically.

## Author
Developed by GunturDeveloper. Feel free to contribute or suggest improvements!

