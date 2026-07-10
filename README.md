<div align="center">

<h1>이민서 · Minseo Lee</h1>

<h3>AI Automation Engineer<br>Technical Art &amp; Tooling</h3>

<p>
  <strong>Godot·Python으로 반복 제작을 자동화하고,<br>
  AI 결과를 실제 런타임에서 검증 가능한 파이프라인으로 만듭니다.</strong>
</p>

<p>
  <a href="https://minseo-log.vercel.app"><img src="https://img.shields.io/badge/BUILD_LOG-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Build log"></a>
  <a href="mailto:mindsurf0176@gmail.com"><img src="https://img.shields.io/badge/EMAIL-1F6FEB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

</div>

---

## Flagship · Vesper Asset Pipeline

<p align="center">
  <a href="https://github.com/mindsurf0176-ui/vesper">
    <img src="https://raw.githubusercontent.com/mindsurf0176-ui/vesper/master/screenshots/godot-runtime.png" width="100%" alt="Vesper Godot runtime capture">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATES-6-17365D?style=flat-square" alt="6 states">
  <img src="https://img.shields.io/badge/FRAMES-33-17365D?style=flat-square" alt="33 frames">
  <img src="https://img.shields.io/badge/PYTHON_TOOLS-16-17365D?style=flat-square" alt="16 Python tools">
  <img src="https://img.shields.io/badge/QA-GODOT_RUNTIME-2F6F55?style=flat-square&logo=godotengine&logoColor=white" alt="Godot runtime QA">
</p>

AI로 만든 캐릭터를 정지 이미지로 붙이는 대신, 상태별 스프라이트를 반복 생성하고 공통 박스·발 위치로 결정적 조립한 뒤 Godot 4.6.2에서 import·smoke·runtime capture까지 검증합니다.

**Problem** 프레임마다 달라지는 캐릭터·무기 형태<br>
**Decision** 4개 접근 비교 후 상태 기반 픽셀 애니메이션 채택<br>
**Proof** 6상태 · 33프레임 · 16개 Python 도구 · 5,573 LOC

**[파이프라인과 실제 결과 보기 →](https://github.com/mindsurf0176-ui/vesper)**

## Core tools

<p>
  <img src="https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white" alt="Godot">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift">
  <img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX Runtime">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

## How I work

**Problem** → measurable baseline → deterministic pipeline → runtime QA → production feedback
