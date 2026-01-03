# RoadRash (OpenGL / GLUT)

> **Course/Assignment:** Assignment 1 Parallax  
> **Author:** Ritvik  
> **Language/Tech:** C++, OpenGL, GLUT / FreeGLUT

---

## 1) Overview

This repository contains an OpenGL/GLUT-based game or assignment developed in C++.

### Project-Specific Description
> Implemented Parallax background for 3D depth effect

---

## 2) Requirements / Dependencies

- C++ Compiler (GCC / MinGW / MSVC)
- OpenGL
- GLUT or FreeGLUT
- Code::Blocks (recommended for Windows users)

---

## 3) How to Build & Run

### Option A — Windows (Code::Blocks)
1. Install **Code::Blocks** with **MinGW**.
2. Open `Assignment1_PRLX.cbp` in Code::Blocks.
3. Make sure the compiler is properly configured.
4. Click **Build & Run (F9)**.

### Option B — Windows (Command Line – MinGW)
```bash
g++ main.cpp -o RoadRash.exe -lopengl32 -lglu32 -lfreeglut
