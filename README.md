# 🐍 Worm Game — Normal Map Implementation for 3D Objects

![OpenGL](https://img.shields.io/badge/OpenGL-3.3%2B-blue)
![GLFW](https://img.shields.io/badge/GLFW-Library-orange)
![GLM](https://img.shields.io/badge/GLM-Math-lightgrey)
![stb_image](https://img.shields.io/badge/stb_image-HeaderOnly-brightgreen)

---

## 🎮 Overview
**Worm Game** is a 3D graphics project that demonstrates **Normal Map Implementation** using modern **OpenGL**.  
The prototype renders a textured 3D worm model with diffuse and normal maps to enhance lighting realism on low-poly surfaces.

This project is developed as part of a **Bachelor’s Diploma Project**.

---

## ✨ Features
- 3D rendering using **OpenGL Core Profile**
- **Normal mapping** for realistic lighting
- Diffuse and normal texture loading with **stb_image**
- Modular shader and texture system
- Cross-platform support (Windows, Linux, macOS)

---

## 🧩 Technologies Used
| Component | Library |
|------------|----------|
| Graphics API | OpenGL 3.3+ |
| Window/Input | GLFW |
| Math Library | GLM |
| Image Loading | stb_image.h |
| Build System | Makefile / Visual Studio |

---

## 🗂️ Project Structure
```plaintext
OpenGl2.0/
├── include/
│   ├── glm/
│   └── stb_image.h
├── resources/
│   ├── worm_diffuse.png
│   └── worm_normal.png
├── shaders/
│   ├── vertex.glsl
│   └── fragment.glsl
├── main.cpp
├── Makefile
└── README.md
