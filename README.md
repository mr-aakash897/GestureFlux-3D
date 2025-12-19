# GestureFlux 3D

GestureFlux 3D is a real-time, gesture-controlled 3D particle visualization built for the web. It uses computer vision and WebGL to let users manipulate complex particle formations using natural hand movements captured through a webcam—no controllers or hardware required.<br>

This project was created for fun and experimentation, with assistance from Google Studio AI, Perplexity, and ChatGPT, exploring the creative potential of AI-assisted development and real-time web graphics.

## ✨ Features

<ul><li>One-Hand Gesture Control<br>
-Thumb + index finger pinch controls particle scale (expand / contract)<br>
-Finger movement controls rotation and motion</li>

<li>Real-Time 3D Particle System<br>
-Powered by Three.js<br>
-Smooth animations with low latency</li>

<li>Multiple Particle Templates<br>
-Hearts<br>
-Flowers<br>
-Saturn Rings<br>
-Buddha Form<br>
-Fireworks</li>

<li>Live Color Customization<br>
-Change particle colors instantly using a color picker</li>

<li>Modern, Minimal Interface<br>
-Clean UI overlay<br>
-Webcam preview with mirrored view<br>
-Performance-optimized rendering</li></ul>

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

<li>Open index.html → Right-click → "Open with Live Server"</li>

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

## 👤 Author

Aakash Chouhan<br>
Software Developer | Web & 3D Experiences
