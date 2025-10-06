# 🐍 Worm Game — Normal Map Implementation for 3D Objects

## 🎮 Overview
This project is a **3D Worm Game** prototype demonstrating **Normal Mapping** in OpenGL.  
It uses **GLFW**, **GLM**, and **stb_image** to render a textured worm model with both diffuse and normal maps.  

The goal is to visualize how normal maps enhance lighting realism on low-poly 3D surfaces.

---

## 🧱 Features
- 3D rendering using modern OpenGL (Core Profile)
- Diffuse and normal texture mapping
- Simple worm body model
- Camera movement and basic lighting
- Modular shader and texture loading

---

## 🧩 Technologies
| Component | Library |
|------------|----------|
| Graphics | OpenGL 3.3+ |
| Window/Input | GLFW |
| Math | GLM |
| Image Loading | stb_image.h |
| Build System | Makefile or Visual Studio |

---

## 🗂️ Project Structure

OpenGl2.0/
├── include/
│ ├── glm/
│ └── stb_image.h
├── resources/
│ ├── worm_diffuse.png
│ └── worm_normal.png
├── shaders/
│ ├── vertex.glsl
│ └── fragment.glsl
├── main.cpp
├── Makefile
└── README.md
