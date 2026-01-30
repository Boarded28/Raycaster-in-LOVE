# Raycaster Demo v1.0

> **Developer:** [@Boarded28](https://github.com/Boarded28)  
> **Version:** 1.0

---

## 🚀 How to Start
To run the demo, simply execute:
`Raycaster.exe`

> [!IMPORTANT]
> Ensure all **.dll** files remain in the root folder! The engine requires these libraries to interface with the LÖVE framework.

---

## 🎮 Controls
| Action | Input |
| :--- | :--- |
| **Move Forward/Backward** | `W` / `S` |
| **Turn Left/Right** | `A` / `D` |
| **Extended Help** | `H` |

---

## 📖 About
This is a **raycasting engine built from scratch** using Lua and the [LÖVE framework](https://love2d.org/). 

This project was developed as a deep dive into game engine architecture, specifically focusing on how to render a 3D environment from 2D data using trigonometric calculations.



### Core Mechanics
The engine works by casting individual rays across the player's field of view (FOV). For every vertical slice of the screen, the engine:
1. Calculates the distance to the nearest wall.
2. Adjusts for "fish-eye" distortion.
3. Scales the height of the wall slice based on that distance.

## ⚖️ License
This software incorporates the **LÖVE framework** (Zlib License).
