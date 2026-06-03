#Flash Detector (iPhone Web App)

This is a simple web-based LED flash detector that uses the iPhone camera to detect sudden changes in brightness and converts them into a sound signal (beep).

## Features

- Uses rear camera (environment mode)
- Real-time brightness analysis from video stream
- Adaptive flash detection algorithm
- Audio beep triggered on detected light flashes
- Works directly in Safari via GitHub Pages

## How it works

The app:
1. Captures video from the camera
2. Calculates average brightness of each frame
3. Compares brightness changes over time
4. Detects sudden spikes (light flashes)
5. Plays a short beep sound when a flash is detected

## Usage

1. Open the GitHub Pages link of this repository
2. Click **Start**
3. Allow camera access
4. Point the camera at a flashing LED or light source

## Notes

- Works best with rear camera
- Requires HTTPS (GitHub Pages provides this automatically)
- Performance may vary depending on lighting conditions and device

## Purpose

This project is intended for experimentation with real-time computer vision on mobile devices using only browser technologies (JavaScript, WebRTC, Canvas API).
