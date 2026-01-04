# DirectX 11 Graphics Renderer

<p align="center">
  <img src="https://img.shields.io/badge/DirectX-11-blue?style=flat-square&logo=windows" alt="DirectX 11"/>
  <img src="https://img.shields.io/badge/C++-20-00599C?style=flat-square&logo=cplusplus" alt="C++20"/>
  <img src="https://img.shields.io/badge/HLSL-Shader-purple?style=flat-square" alt="HLSL"/>
  <img src="https://img.shields.io/badge/Visual%20Studio-2019-5C2D91?style=flat-square&logo=visualstudio" alt="VS2019"/>
</p>

A DirectX 11-based 3D rendering pipeline built during the **Game Graphics Programming** course at Kyung Hee University.

> 경희대학교 소프트웨어융합학과 **게임 그래픽 프로그래밍** 수업에서 구현한 DirectX 11 기반 3D 렌더링 파이프라인입니다.

---

## 🎯 Overview

This project covers the full spectrum of real-time 3D graphics, from basic window creation to advanced rendering techniques including skeletal animation, normal mapping, and shadow mapping.

> 윈도우 생성부터 스켈레탈 애니메이션, 노멀 맵핑, 그림자 맵핑까지 실시간 3D 그래픽스의 전반을 다룹니다.

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Graphics API | DirectX 11 |
| Language | C++20, HLSL |
| Library | Assimp (Open Asset Import Library) |
| IDE | Visual Studio 2019 |

---

## 📚 Labs

### Foundation

| Lab | Topic | Description |
|-----|-------|-------------|
| 01 | Window Creation | Create a window using Windows API |
| 02 | OOP Refactoring | Restructure codebase with object-oriented design |
| 03 | Triangle Rendering | Build basic primitive rendering pipeline |

<p align="center">
  <img src="./image/lab03.png" width="400" alt="Triangle Rendering"/>
</p>

### 3D Rendering Pipeline

| Lab | Topic | Description |
|-----|-------|-------------|
| 04 | Transform Matrices | Apply World, View, Projection matrices |
| 05 | Texture Mapping | UV coordinate-based texture sampling |
| 06 | Phong Shading | Implement Ambient, Diffuse, Specular lighting model |

<p align="center">
  <img src="./image/lab04.png" width="300" alt="3D Object"/>
  <img src="./image/lab05.png" width="300" alt="Texture Mapping"/>
  <img src="./image/lab06.png" width="300" alt="Phong Shading"/>
</p>

### Advanced Techniques

| Lab | Topic | Description |
|-----|-------|-------------|
| 07 | Model Import | Load 3D models via Assimp library |
| 08 | Skeletal Animation | Bone hierarchy and skinning animation |
| 09 | Normal Mapping | Tangent space-based normal map application |
| 10 | Shadow Mapping | Depth buffer-based real-time shadows |

<p align="center">
  <img src="./image/lab07.png" width="300" alt="Model Import"/>
  <img src="./image/lab08.png" width="300" alt="Skeletal Animation"/>
</p>

<p align="center">
  <img src="./image/lab09.png" width="300" alt="Normal Mapping"/>
  <img src="./image/lab10.png" width="300" alt="Shadow Mapping"/>
</p>

---

## 🏆 Assignments

### Assignment 01: Interactive Camera System
Real-time camera controller with user input processing.
> 매 프레임 사용자 입력을 처리하는 인터랙티브 카메라 시스템

<p align="center">
  <img src="./image/ass01.png" width="500" alt="Camera System"/>
</p>

### Assignment 02: Voxel Map with Instancing
Optimized voxel map rendering using Instance Buffers to minimize Draw Calls.
> Instance Buffer를 활용한 복셀 맵 렌더링 및 Draw Call 최적화

<p align="center">
  <img src="./image/ass02.png" width="500" alt="Voxel Map"/>
</p>

### Assignment 03: Advanced Rendering Techniques

| Feature | Description |
|---------|-------------|
| **Light Attenuation** | Distance-based light falloff (Constant, Linear, Quadratic) |
| **Skybox** | Cube map-based environment background |
| **Reflection Mapping** | Real-time environment reflection using cube maps |

> 거리 기반 광원 감쇠, 큐브맵 스카이박스, 환경 반사 매핑 구현

<p align="center">
  <img src="./image/ass03.png" width="280" alt="Light Attenuation"/>
</p>

---

## 🚀 Getting Started

> ⚠️ **Windows only**

1. **Clone** the repository
   ```bash
   git clone https://github.com/[username]/DirectX11_Renderer.git
   ```

2. **Checkout** to desired Lab or Assignment
   ```bash
   git checkout [LAB0X]  # or [ASS0X]
   ```

3. **Open** the solution in Visual Studio 2019

4. **Set** `Game` project as Startup Project and run

---

## 📁 Project Structure

```
DirectX11_Renderer/
├── Game/
│   ├── Shaders/          # HLSL shader files
│   ├── Assets/           # 3D models, textures
│   └── Source/           # C++ source code
├── Library/              # External libraries (Assimp, etc.)
└── images/               # Screenshots for README
```

---

## 📖 Key Learnings

- Complete understanding of DirectX 11 rendering pipeline
- Vertex/Pixel shader programming with HLSL
- Practical experience with real-time graphics optimization techniques

> DirectX 11 렌더링 파이프라인의 전체 흐름, HLSL 셰이더 프로그래밍, 실시간 그래픽스 최적화 기법 학습

---

<p align="center">
  <sub>Spring 2022 · Kyung Hee University, Dept. of Software Convergence</sub>
</p>
