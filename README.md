# Highway Havoc – 3D OpenGL Python Game

A 3D endless highway driving game built with PyOpenGL and GLUT. Dodge traffic, manage your speed and fuel, and experience dynamic environments!

## Features

- 3D graphics using OpenGL (PyOpenGL, GLUT)
- Multiple vehicle types (buses, sedans, trucks)
- Four dynamic environments: Marine Drive, Ice Hill, Desert, Night Rain
- Speed boost with fuel management and refill delay
- Multiple camera modes: third-person, first-person, rear view
- Realistic traffic with collision detection
- Score, distance, and high score tracking
- Keyboard controls for all actions
- Game over and restart functionality

## Requirements

- Python 3.7+
- PyOpenGL
- PyOpenGL_accelerate (optional, for better performance)
- FreeGLUT (or GLUT) installed on your system

## Installation

1. **Install Python**  
   Download and install Python from https://www.python.org/ if not already installed.

2. **Install PyOpenGL and GLUT**  
   Open a terminal and run:
   ```
   pip install PyOpenGL PyOpenGL_accelerate
   ```
   For Windows, install FreeGLUT:
   - Download from http://www.transmissionzero.co.uk/software/freeglut-devel/
   - Extract and place the DLLs (e.g., freeglut.dll) in your Python or system PATH.

3. **Clone or Download this Repository**
   ```
   git clone <your-repo-url>
   cd <repo-folder>
   ```

## How to Run

1. Open a terminal in the project directory.
2. Run:
   ```
   python Sec25_22101111-22101360-24241330_Summer2025.py
   ```
   The game window should appear.

## How to Play

- **Move Left/Right:**  
  A / D keys

- **Accelerate/Decelerate:**  
  W / S keys (hold to accelerate/decelerate)

- **Pause/Resume:**  
  P key

- **Camera Modes:**  
  1 = Third-person  
  2 = First-person  
  3 = Rear view

- **Speed Boost:**  
  B key (if fuel is available)

- **Change Environment:**  
  C = Marine Drive  
  X = Desert  
  Z = Ice Hill  
  N = Night Rain

- **Restart Game:**  
  R key (after game over)

- **Quit Game:**  
  Q key (after game over)

## Game Instructions

- Avoid colliding with other vehicles.
- Use boost wisely; fuel is limited and takes time to refill.
- Try different camera modes for unique perspectives.
- The environment changes automatically every 60 seconds, or you can switch manually.
- Your score and high score are displayed on the screen.

## Troubleshooting

- If you get errors about missing GLUT or DLLs, ensure FreeGLUT is installed and its DLL is in your PATH.
- For best performance, install PyOpenGL_accelerate.

## License

This project is for educational purposes.
