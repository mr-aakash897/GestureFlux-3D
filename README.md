# GestureFlux 3D

GestureFlux 3D is a real-time, gesture-controlled 3D particle visualization built for the web. It uses computer vision and WebGL to let users manipulate complex particle formations using natural hand movements captured through a webcam—no controllers or hardware required.

## ✨ Features

One-Hand Gesture Control

Thumb + index finger pinch controls particle scale (expand / contract)

Finger movement controls rotation and motion

Real-Time 3D Particle System

Powered by Three.js

Smooth animations with low latency

Multiple Particle Templates

Hearts

Flowers

Saturn Rings

Buddha Form

Fireworks

Live Color Customization

Change particle colors instantly using a color picker

Modern, Minimal Interface

Clean UI overlay

Webcam preview with mirrored view

Performance-optimized rendering

## 🧠 How It Works

Camera Capture
The browser accesses your webcam to capture live video frames.

Hand Tracking
MediaPipe detects hand landmarks (thumb, index finger, etc.) in real time.

Gesture Recognition

Distance between thumb and index finger determines particle expansion

Finger movement affects rotation and dynamics

Particle Response
The 3D particle system updates instantly based on gesture input.

## 🛠 Tech Stack

Three.js — 3D rendering (WebGL)

MediaPipe Hands — Real-time hand tracking

JavaScript (ES Modules)

HTML5 + CSS3

Web APIs (getUserMedia)

## 🚀 How to Run

### ⚠️ Webcam access requires HTTPS or localhost

### Option 1: Local Server (Recommended)
#### Using VS Code Live Server
Open index.html → Right-click → "Open with Live Server"

#### OR using Python
python -m http.server


Then open:

http://localhost:8000

### Option 2: Deploy Online

#### Deploy using:

Netlify

Vercel

GitHub Pages (with HTTPS)

## 🖐 How to Use Gestures
Gesture	Action
Thumb + Index close	-> Contract particles
Thumb + Index spread -> Expand particles
Finger movement ->	Rotate particle system
GUI panel -> Change template, color, size

#### Use one hand, keep it clearly visible in the camera frame.

## ⚠️ Requirements

<ul><li>Desktop or laptop with webcam</li>

<li>Modern browser (Chrome / Edge recommended)</li>

<li>Good lighting for accurate hand tracking</li></ul>

## 📌 Known Limitations

<ul><li>Works best in good lighting</li>
<li>Mobile browsers may have limited performance</li>
<li>Requires camera permission</li></ul>

