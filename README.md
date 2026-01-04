# DirectX 11 Graphics Renderer

<p align="center">
  <img src="https://img.shields.io/badge/DirectX-11-blue?style=flat-square&logo=windows" alt="DirectX 11"/>
  <img src="https://img.shields.io/badge/C++-20-00599C?style=flat-square&logo=cplusplus" alt="C++20"/>
  <img src="https://img.shields.io/badge/HLSL-Shader-purple?style=flat-square" alt="HLSL"/>
  <img src="https://img.shields.io/badge/Visual%20Studio-2019-5C2D91?style=flat-square&logo=visualstudio" alt="VS2019"/>
</p>

경희대학교 소프트웨어융합학과 **게임 그래픽 프로그래밍** 수업에서 구현한 DirectX 11 기반 3D 렌더링 파이프라인입니다.

---

## 🎯 프로젝트 목표

- DirectX 11 그래픽스 파이프라인의 핵심 개념 학습 및 구현
- 실시간 3D 렌더링 기법 (조명, 그림자, 애니메이션) 적용
- 최적화 기법 (인스턴싱, Draw Call 최소화) 실습

---

## 🛠 기술 스택

| 분류 | 기술 |
|------|------|
| Graphics API | DirectX 11 |
| Language | C++20, HLSL |
| Library | Assimp (Open Asset Import Library) |
| IDE | Visual Studio 2019 |

---

## 📚 구현 내용

### Foundation

| Lab | 주제 | 핵심 내용 |
|-----|------|----------|
| 01 | Window Creation | Windows API를 활용한 윈도우 생성 |
| 02 | OOP Refactoring | 객체지향 설계로 코드 구조화 |
| 03 | Triangle Rendering | 기본 프리미티브 렌더링 파이프라인 구축 |

### 3D Rendering Pipeline

| Lab | 주제 | 핵심 내용 |
|-----|------|----------|
| 04 | Transform Matrices | World, View, Projection 변환 행렬 적용 |
| 05 | Texture Mapping | UV 좌표 기반 텍스처 샘플링 |
| 06 | Phong Shading | Ambient, Diffuse, Specular 조명 모델 |

### Advanced Techniques

| Lab | 주제 | 핵심 내용 |
|-----|------|----------|
| 07 | Model Import | Assimp 라이브러리를 통한 3D 모델 로딩 |
| 08 | Skeletal Animation | 본 계층 구조 및 스키닝 애니메이션 |
| 09 | Normal Mapping | 탄젠트 공간 기반 노멀 맵 적용 |
| 10 | Shadow Mapping | 깊이 버퍼 기반 실시간 그림자 |

---

## 🏆 Assignments

### Assignment 01: Camera System
- 매 프레임 사용자 입력을 처리하는 인터랙티브 카메라 컨트롤러 구현
- FPS 스타일 카메라 이동 및 회전

### Assignment 02: Voxel Map with Instancing
- Instance Buffer를 활용한 복셀 맵 렌더링
- Draw Call 최소화를 통한 렌더링 성능 최적화

### Assignment 03: Advanced Rendering
| 기능 | 설명 |
|------|------|
| **Light Attenuation** | 거리 기반 광원 감쇠 (Constant, Linear, Quadratic) |
| **Skybox** | Cube Map 기반 환경 배경 렌더링 |
| **Reflection Mapping** | Cube Map을 활용한 실시간 환경 반사 |

---

## 🚀 실행 방법

1. 저장소 클론
   ```bash
   git clone https://github.com/[username]/DirectX11_Renderer.git
   ```

2. 원하는 Lab/Assignment로 체크아웃
   ```bash
   git checkout [LAB0X]  # 또는 [ASS0X]
   ```

3. Visual Studio 2019에서 솔루션 열기

4. `Game` 프로젝트를 **시작 프로젝트로 설정** 후 실행

> ⚠️ Windows 운영체제에서만 실행 가능합니다.

---

## 📁 프로젝트 구조

```
DirectX11_Renderer/
├── Game/                 # 메인 게임 프로젝트
│   ├── Shaders/          # HLSL 셰이더 파일
│   ├── Assets/           # 3D 모델, 텍스처
│   └── Source/           # C++ 소스 코드
└── Library/              # 외부 라이브러리 (Assimp 등)
```

---

## 📖 학습 성과

- DirectX 11 렌더링 파이프라인의 전체 흐름 이해
- Vertex/Pixel Shader 작성 및 Constant Buffer 활용
- 실시간 그래픽스 최적화 기법 적용 경험

---

<p align="center">
  <sub>2022년 1학기 · 경희대학교 소프트웨어융합학과</sub>
</p>
