Olympic Shooting Range 3D Game
This is a 3D Computer Graphics project built using Python and PyOpenGL. It simulates an interactive shooting range where users can aim and shoot at various targets to achieve a high score.

✨ Key Features
3D Environment: Includes a detailed shooting booth, floor, side walls, and a ceiling to create an immersive range experience.

Diverse Target Types:

Standard Targets: Circular targets with varying point values based on size.

Triangle Targets: High-value targets worth +20 points.

Moving Targets: Oscillating targets that add difficulty, worth +12 points.

Bomb Targets: Hazard targets that subtract -15 points if hit.

Dynamic Weather System: Press the 'R' key to toggle a real-time rain effect within the 3D space.

Audio Integration: Features realistic sound effects for gunfire and explosions, plus a continuous background music track using the Pygame mixer.

Interactive HUD: A dedicated 3D Head-Up Display (HUD) on the walls shows the current score, high score, and game instructions.

🎮 Game Controls
Mouse Movement: Aim the crosshair.

Left Click: Fire a bullet.

Space Bar: Start or Pause/Resume the game.

Tab Key: Restart the game session.

'R' Key: Toggle rain effect ON/OFF.

ESC Key: Exit the application.

🛠 Tech Stack
Language: Python

Graphics: PyOpenGL (OpenGL 2.1 / GLUT)

Sound & Logic: Pygame

Math: Trigonometry for 3D trajectories and collisions

🚀 Installation and Usage
1. Prerequisites: Ensure you have Python installed on your system.
2. Install Dependencies: Run the following command to install the required libraries:
    pip install PyOpenGL PyOpenGL_accelerate pygame
3. Required Assets: Place the following audio files in the same directory as the script:
     - gun_fire.wav
     - bomb_blast.wav
     - background.mp3
4. Run the Game
