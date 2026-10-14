
Singularity — Schwarzschild Black Hole Visualizer
A real-time, browser-based WebGL renderer that simulates the visual appearance of a Schwarzschild black hole using null-geodesic ray tracing. The camera is positioned at a 30° tilt, allowing you to explore the photon ring, shadow, and innermost stable circular orbit (ISCO) from a dynamic perspective.

🔗 Live Site: https://nikhiltomar2712.github.io/blackhole1/

✨ Features
Real-time null-geodesic rendering of a Schwarzschild (non-rotating) black hole

Interactive camera controls

🖱️ Drag — Orbit around the black hole

🔍 Scroll / Pinch — Move closer or further away

Live telemetry HUD displaying:

Observer distance (R.OBS)

Inclination (INCL) and Azimuth (AZIM)

Photon Ring radius (1.50 rs)

Shadow diameter (5.20 rs)

ISCO radius (3.00 rs)

FPS counter and mission-elapsed time

30° camera tilt for a cinematic, off-axis view of the accretion geometry

GPU-accelerated — requires WebGL support

🚀 Usage
Open the live site in a modern browser (Chrome, Firefox, Edge, Safari).

Drag anywhere on the canvas to orbit the black hole.

Scroll (desktop) or pinch (mobile) to change your distance from the event horizon.

Watch the HUD update in real time as you move through spacetime.

⚠️ Note: A GPU with WebGL acceleration is required. If you see "WebGL unavailable", enable hardware acceleration in your browser settings.

🧠 Physics Background
This visualization is based on the Schwarzschild metric, which describes the spacetime geometry around a non-rotating, uncharged black hole. The renderer traces null geodesics — the paths that light rays follow — backward from the observer's camera to determine what photons reach the eye.

Key reference radii (in units of the Schwarzschild radius rs = 2GM/c²):

Feature	Value
Photon Ring	1.50 rs
Shadow Diameter	5.20 rs
ISCO	3.00 rs
These match the theoretical predictions for a Schwarzschild black hole.

🛠️ Tech Stack
WebGL / GLSL — GPU shaders for geodesic integration

JavaScript — camera controls, HUD, and rendering loop

HTML / CSS — minimal UI overlay

📄 License
This project is released under the MIT License. See the LICENSE file for details.

🙏 Acknowledgements
Inspired by the visual legacy of Interstellar (2014), the Event Horizon Telescope collaboration, and the broader open-source physics-visualization community.

📬 Contact
Created by Nikhil Tomar
GitHub: @nikhiltomar2712
