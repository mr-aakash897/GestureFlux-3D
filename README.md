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

<ul><li>Camera Capture<br>
-The browser accesses your webcam to capture live video frames.</li>

<li>Hand Tracking<br>
-MediaPipe detects hand landmarks (thumb, index finger, etc.) in real time.</li>

<li>Gesture Recognition<br>
-Distance between thumb and index finger determines particle expansion<br>
-Finger movement affects rotation and dynamics</li>

<li>Particle Response<br>
-The 3D particle system updates instantly based on gesture input.</li></ul>

## 🛠 Tech Stack

<ul><li>Three.js — 3D rendering (WebGL)</li>
<li>MediaPipe Hands — Real-time hand tracking</li>
<li>JavaScript (ES Modules)</li>
<li>HTML5 + CSS3</li>
<li>Web APIs (getUserMedia)</li></ul>

## 🚀 How to Run

### ⚠️ Webcam access requires HTTPS or localhost

### Option 1: Local Server (Recommended)
#### Using VS Code Live Server
<li>Open index.html → Right-click → "Open with Live Server"</li>

#### OR using Python
<li>python -m http.server<br></li>

<li>Then open:<br>
http://localhost:8000</li>

### Option 2: Deploy Online

#### Deploy using:

<ul><li>Netlify</li>
<li>Vercel</li>
<li>GitHub Pages (with HTTPS)</li></ul>

## 🖐 How to Use Gestures
<ul><li>Gesture	Action</li>
<li>Thumb + Index close	-> Contract particles</li>
<li>Thumb + Index spread -> Expand particles</li>
<li>Finger movement ->	Rotate particle system</li>
<li>GUI panel -> Change template, color, size</li></ul>

#### Use one hand, keep it clearly visible in the camera frame.

## ⚠️ Requirements

<ul><li>Desktop or laptop with webcam</li>
<li>Modern browser (Chrome / Edge recommended)</li>
<li>Good lighting for accurate hand tracking</li></ul>

## 📌 Known Limitations

<ul><li>Works best in good lighting</li>
<li>Mobile browsers may have limited performance</li>
<li>Requires camera permission</li></ul>

