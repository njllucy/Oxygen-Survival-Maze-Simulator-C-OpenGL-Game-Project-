# Oxygen Survival Maze Simulator (C++ OpenGL)

A 2D underwater survival game developed using **C++ and OpenGL (GLUT)**.
The player controls a submarine navigating through a maze while managing oxygen,
avoiding hazards, and reaching the exit before time runs out.

---

## ▶ Demo Video 
https://youtu.be/ObSlHNgKFtc


## 🎮 Gameplay Overview
The goal is to survive underwater by:
- Collecting oxygen tanks
- Avoiding moving hazards
- Navigating maze blockades
- Reaching the exit door within the given time

The game ends when oxygen runs out or time expires.
A win or game-over message is displayed in large bold center text.

---

## ✨ Features
- 2D OpenGL rendering
- Maze-style blockades
- Oxygen management system
- Randomly spawning hazards and oxygen tanks
- Particle effects (bubbles)
- Countdown timer with alert
- Textured objects using `stb_image`
- Keyboard-based controls

---

## 🕹 Controls
| Key | Action |
|----|-------|
| U | Move Up |
| D | Move Down |
| L | Move Left |
| R | Move Right |
| P | Pause / Resume |
| R | Restart (after win/lose) |
| ESC | Exit Game |

---

## 🛠 Technologies Used
- C++
- OpenGL
- GLUT
- stb_image.h

---

## ▶ How to Run
1. Install Code::Blocks or any C++ compiler with OpenGL support
2. Link OpenGL and GLUT libraries
3. Place texture files in the same directory:
   - submarine.png
   - tank.png
   - hazard.png
   - door.png
   - bubble.png
4. Compile and run the project


