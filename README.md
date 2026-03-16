# ✨ Gesture Controlled Particle System

A high-performance interactive 3D particle visualizer built with **Three.js** and **MediaPipe Hands**. This project allows users to manipulate a cloud of 10,000 particles using real-time hand gestures captured via webcam.

## 🚀 Features

* **Real-time Hand Tracking:** Uses Google MediaPipe for low-latency gesture detection.
* **Dynamic Morphing:** Smoothly transitions between five geometric states:
* **SPHERE** | **HEART** | **SATURN** | **TORUS** | **FLOWER**


* **Physics Interaction:** * **Disturb:** Move your index finger to repel particles.
* **Pinch (Attract):** Pinch your thumb and index finger to pull particles toward your hand and trigger a "heat" color shift.
* **Scale:** Opening your hand wider scales the entire particle system up.


* **Gesture Switching:** Hold an open hand for 2 seconds to cycle to the next shape.

## 🛠️ Tech Stack

* **Three.js**: For 3D rendering and custom particle shaders.
* **MediaPipe Hands**: For ML-based hand landmark detection.
* **HTML5/CSS3**: For the HUD (Heads-Up Display) and UI overlays.

## 📦 Setup & Usage

1. **Clone the project:**
```bash git clone https://github.com/your-username/particle-vision.git

```


2. **Open the file:** Simply open `particles.html` in any modern web browser (Chrome/Edge recommended).
3. **Interaction Guide:**
* **Move Hand:** Hover over particles to disturb them.
* **Pinch:** Attract particles and turn them red.
* **Open Hand:** Trigger a shape change after 2 seconds.



## ⚙️ Customization

You can tweak the system by editing these constants in the script:

* `PARTICLE_COUNT`: Default is `10000`. Increase for more density (requires better GPU).
* `MORPH_SPEED`: Adjusts how fast shapes transform.
* `PARTICLE_SIZE`: Changes the scale of the individual points. 
