# Three.js Open World Monster Driver 🚗👾

A simple open-world driving game built purely with Three.js, running directly in the browser. Drive your customizable car, avoid procedurally generated obstacles and chase monsters, and survive as long as possible!

## Live Demo ✨

Play the game live here: 
**[https://vesuvius13.github.io/open-world-driver/](https://vesuvius13.github.io/open-world-driver/)** 

## Features

*   Infinite open world with a grid floor and procedurally generated obstacles.
*   Basic car model with customizable color selected at the start.
*   Keyboard controls (WASD/Arrows) for acceleration, braking, and steering.
*   Monsters that spawn and chase the player after reaching a score threshold (30 points).
*   Collision detection with obstacles and monsters results in Game Over.
*   Score based on survival time (in seconds/points).
*   Gradually increasing maximum car speed based on the current score.
*   Start Menu, Color Selection screen, and Game Over screen.
*   Built purely with Three.js (r161) loaded via CDN – no external assets or textures downloaded.
*   Simple third-person camera that follows the car.
*   Basic lighting and shadows.

## Controls

*   **W / Up Arrow:** Accelerate
*   **S / Down Arrow:** Brake / Reverse
*   **A / Left Arrow:** Steer Left
*   **D / Right Arrow:** Steer Right
*   **Enter / Space (on Game Over):** Restart (takes you back to Start Menu)

## Technology Stack

*   [Three.js](https://threejs.org/) (r161 via UNPKG CDN)
*   HTML5
*   CSS3
*   JavaScript (ES Modules)

## Running Locally

Because this project uses JavaScript ES Modules (`import * as THREE from '...'`), you **cannot** simply open the `index.html` file directly in your browser from the filesystem (`file:///...`). You need to serve it through a local web server.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/<vesuvius13>/<open-world-driver>.git
    cd <your-repo-name>
    ```
    *(Replace with your actual username and repo name)*

2.  **Use a simple local server:** The easiest way is often using Node.js:
    *   Make sure you have [Node.js](https://nodejs.org/) installed.
    *   Open your terminal in the project directory (`open-world-driver`).
    *   Run the following command:
        ```bash
        npx serve
        ```
    *   This will start a local server, usually at `http://localhost:3000` or a similar address (it will be shown in the terminal).

3.  **Alternatively (VS Code):**
    *   If you use Visual Studio Code, you can install the **"Live Server"** extension.
    *   Right-click on the `index.html` file in the VS Code explorer and choose "Open with Live Server".

4.  **Open in browser:** Navigate to the local URL provided by your server (e.g., `http://localhost:3000`).

## License

This project is open source and available under the [MIT License](LICENSE). 
*(Consider adding a file named `LICENSE` with the MIT License text if you want to be explicit).*

---

Enjoy driving!
