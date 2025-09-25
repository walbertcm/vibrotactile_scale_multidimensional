📄 README
Vibrotactile Scale Multidimensional

Repository for experimental design, implementation, and analysis of multidimensional vibrotactile scales based on psychophysical methods.

This project investigates the construction of vibrotactile scales grounded in perceptual thresholds (absolute limits, JNDs, and terminal limits) and their combination into bi- and three-dimensional arrangements.

🔎 What the algorithm does
Renders a 3D scene with Three.js (three.module.js + OrbitControls.js).
Creates a 3D grid (values for X, Y, Z).

Allows configuration of:
shape (cube/sphere),
colors (edges, fill, background),
size, spacing, and line thickness,
labels (text in cells).

Provides options to select diagonals and axes using the 3D Bresenham algorithm.
Displays a list of selected triples.
Maintains interaction with OrbitControls (rotate/zoom the scene).

▶️ How to run it in Visual Studio Code with Live Server
Install VS Code (if not already installed).
Install the Live Server extension:
Open VS Code → Extensions (Ctrl+Shift+X).
Search for Live Server.
Install the extension created by Ritwick Dey.
Open the project folder:
Create a folder and place the file indexV5.html inside it.
In VS Code: File → Open Folder… and select this folder.
Open the HTML file:
Click on indexV5.html.
Run with Live Server:
Right-click in the editor → Open with Live Server.
The browser will automatically open at http://127.0.0.1:5500/indexV5.html.

Test:
You will see the graphical interface in the browser.
You can interact with sliders, checkboxes, and change the values.
The 3D scene is rendered via WebGL (so it requires a modern browser: Chrome, Edge, or Firefox).
