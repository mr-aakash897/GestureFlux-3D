# GestureFlux 3D

GestureFlux 3D is a real-time, gesture-controlled 3D particle visualization built for the web. It uses computer vision and WebGL to let users manipulate complex particle formations using natural hand movements captured through a webcam—no controllers or hardware required.<br>

## ✨ Features

<li><ul>One-Hand Gesture Control<br>
-Thumb + index finger pinch controls particle scale (expand / contract)<br>
-Finger movement controls rotation and motion<br></ul>

<ul>Real-Time 3D Particle System<br>
-Powered by Three.js<br>
-Smooth animations with low latency<br></ul>

<ul>Multiple Particle Templates<br>
-Hearts<br>
-Flowers<br>
-Saturn Rings<br>
-Buddha Form<br>
-Fireworks<br></ul>

<ul>Live Color Customization<br>
-Change particle colors instantly using a color picker<br></ul>

<ul>Modern, Minimal Interface<br>
-Clean UI overlay<br>
-Webcam preview with mirrored view<br>
-Performance-optimized rendering<br></ul><li>

## 🧠 How It Works

<li><ul>Camera Capture<br>
The browser accesses your webcam to capture live video frames.<br></ul>

<ul>Hand Tracking<br>
-MediaPipe detects hand landmarks (thumb, index finger, etc.) in real time.</ul><br>

<ul>Gesture Recognition<br>
-Distance between thumb and index finger determines particle expansion
-Finger movement affects rotation and dynamics</ul><br>

<ul>Particle Response<br>
-The 3D particle system updates instantly based on gesture input.</ul></li>

## 🛠 Tech Stack

<ul>Three.js — 3D rendering (WebGL)</ul>
<ul>MediaPipe Hands — Real-time hand tracking</ul>
<ul>JavaScript (ES Modules)</ul>
<ul>HTML5 + CSS3</ul>
<ul>Web APIs (getUserMedia)</ul>

## 🚀 How to Run

### ⚠️ Webcam access requires HTTPS or localhost

### Option 1: Local Server (Recommended)
#### Using VS Code Live Server
Open index.html → Right-click → "Open with Live Server"

#### OR using Python
python -m http.server<br>


Then open:<br>
http://localhost:8000<br>

### Option 2: Deploy Online

#### Deploy using:
<ul>Netlify</ul>
<ul>Vercel</ul>
<ul>GitHub Pages (with HTTPS)</ul>

## 🖐 How to Use Gestures
#### Gesture	-> Action
<ul>Thumb + Index close	-> Contract particles</ul>
<ul>Thumb + Index spread -> Expand particles</ul>
<ul>Finger movement ->	Rotate particle system</ul>
<ul>GUI panel -> Change template, color, size</ul>

#### Use one hand, keep it clearly visible in the camera frame.

## ⚠️ Requirements

<ul>Desktop or laptop with webcam</ul>
<ul>Modern browser (Chrome / Edge recommended)</ul>
<ul>Good lighting for accurate hand tracking</ul>

## 📌 Known Limitations

<ul>Works best in good lighting</ul>
<ul>Mobile browsers may have limited performance</ul>
<ul>Requires camera permission</ul>

## 👤 Author

Aakash Chouhan<br>
Software Developer | Web & 3D Experiences