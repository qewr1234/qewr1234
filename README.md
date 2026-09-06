<div align="center">

# 이유준

**Embedded SW · Physical AI · Robotics · Edge AI**

정보통신공학을 전공하며,  
**AI/SW를 실제 HW에 연결하고 시스템 수준에서 동작까지 검증하는 엔지니어**를 지향합니다.

</div>

---

## 🏆 Awards & Achievements

| Date | Event | Award / Result | Link |
|:---:|---|---|:---:|
| **2026.09** | 2026 MIDAS CDP 경진대회 | **🏆 우수상** | — |
| **2026.06** | 2026학년도 1학기 MIDAS GROUP 최종발표회 | **🏆 대상 · 총장상** | — |
| **2026.05** | ISET 2026 우수발표논문 | **🏆 장려상** | — |
| **2026.04** | 구조물 안정성 물리 추론 AI 경진대회 | **🥇 1위 / 484팀** | [Repo](https://github.com/qewr1234/dacon-structural-stability-ai) |
| **2025.12** | 제7회 POSTECH OIBC Challenge | **🏆 4위 / 153팀 · 장려상** | [Repo](https://github.com/qewr1234/postech-oibc-solar) |
| **2025.12** | MIDAS GROUP 최종발표회 | **🏆 우수상** | — |
| **2025.09** | LG Aimers 7기 | **온라인 25 / 817 → 본선 12 / 31** | [Repo](https://github.com/qewr1234/LG-Aimers-7th) |
| **2025.06** | Hecto AI Challenge | **90 / 748** | [Repo](https://github.com/qewr1234/hai-vehicle-classification) |

---

## 📌 Featured Repositories

### 🥇 [Structural Stability Physics Reasoning AI](https://github.com/qewr1234/dacon-structural-stability-ai)

다각도 구조물 이미지로부터 **물리적 안정성과 붕괴 가능성을 추론**하는 Multi-View Vision AI 프로젝트입니다.

`front.png`와 `top.png`를 ConvNeXt-Large DINOv3 Backbone으로 처리한 뒤 Attention 기반 View Fusion을 적용하고, LogLoss 최적화를 위해 Label Smoothing과 Temperature Scaling을 사용했습니다.

**🥇 DACON 구조물 안정성 물리 추론 AI 경진대회 1위 / 484팀**

`PyTorch` `ConvNeXt` `DINOv3` `Attention` `Computer Vision`

---

### 🔍 [Dead Pixel Detector](https://github.com/qewr1234/dead-pixel-detector)

LIG D&A PBL에서 수행한 **IIR 센서 RAW 기반 Dead Pixel 검출** 프로젝트입니다.

센서 RAW 데이터의 통계적 특성을 분석하고 규칙·통계 기반 Detector와 결과 비교 Viewer를 구현했습니다.

`Python` `NumPy` `SciPy` `Sensor Data` `Signal Processing`

---

### 🛸 [Leader-Follower Drone](https://github.com/qewr1234/drone-swarm-detection)

**Jetson Orin NX · RealSense D435i · MAVLink** 기반 Leader-Follower 드론 시스템입니다.

영상 기반 Leader 검출·추종과 드론 제어 시스템을 연결하고, 실제 HW/SW 인터페이스 통합 및 시스템 동작 검증을 수행했습니다.

`Python` `Jetson Orin NX` `OpenCV` `RealSense` `MAVLink`

---

### 🤖 [Lightweight VLA](https://github.com/qewr1234/smolvla-fast-lite)

경량 Vision-Language-Action 모델을 **Jetson Orin Nano**에 배포하기 위한 Edge AI 프로젝트입니다.

제한된 연산 자원에서 VLA 모델을 실행하기 위한 모델 경량화, 추론 최적화 및 실시간 실행 환경을 다룹니다.

`PyTorch` `Jetson` `TensorRT` `VLA` `Edge AI`

---

### 🤟 [KSL Recognition](https://github.com/qewr1234/ksl-recognition)

지문자와 음성을 함께 인식하는 **멀티모달 의사소통 시스템**입니다.

MediaPipe 기반 손 특징 추출과 ST-GCN 기반 지문자 인식을 구현하고 음성 인식 모듈과 결합했습니다.

`PyTorch` `OpenCV` `MediaPipe` `ST-GCN` `Multimodal AI`

---

### ☀️ [POSTECH OIBC Solar](https://github.com/qewr1234/postech-oibc-solar)

환경 센서 데이터로부터 **일사량을 추정**하는 Machine Learning 프로젝트입니다.

결측 기상 데이터 처리와 시간·위치·태양 기하 기반 Feature Engineering을 구성하고 LightGBM Tweedie 모델과 Seed Ensemble을 적용했습니다.

**🏆 제7회 POSTECH OIBC Challenge 4위 / 153팀 · 장려상**

`Python` `LightGBM` `Feature Engineering` `Ensemble` `Time Series`

---

### 📊 [LG Aimers 7th](https://github.com/qewr1234/LG-Aimers-7th)

리조트 식음업장의 과거 판매 데이터를 기반으로 **향후 7일 메뉴별 수요를 예측**하는 프로젝트입니다.

시계열 Feature Engineering, LightGBM, Optuna 기반 Hyperparameter Optimization 및 Ensemble을 적용했습니다.

**온라인 25 / 817 → 오프라인 본선 12 / 31**

`Python` `LightGBM` `Optuna` `Time Series` `Ensemble`

---

### 🚗 [Hecto AI Challenge](https://github.com/qewr1234/hai-vehicle-classification)

자동차 이미지를 분류하는 **ConvNeXt 기반 Computer Vision 프로젝트**입니다.

Conv Layer 선택적 Freeze/Unfreeze Fine-Tuning과 다양한 해상도의 모델을 활용한 Probability Ensemble을 적용했습니다.

**90 / 748**

`PyTorch` `ConvNeXt` `timm` `Fine-Tuning` `Computer Vision`

---

## 🎯 Engineering Focus

- **Physical AI** — 실제 환경에서 Perception과 Action을 연결하는 AI 시스템
- **Robotics** — Vision, Sensor, Control을 결합한 로봇 시스템
- **Edge AI** — NVIDIA Jetson 기반 경량 모델 배포 및 추론 최적화
- **Embedded SW** — MCU 및 HW 인터페이스 기반 시스템 구현
- **Computer Vision** — Detection, Recognition, Multi-View Vision
- **Machine Learning** — Tabular / Time-Series Feature Engineering 및 Ensemble

---

## 🛠 Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | `Python` `C` `C++` |
| **AI / ML** | `PyTorch` `LightGBM` `scikit-learn` `timm` |
| **Computer Vision** | `OpenCV` `MediaPipe` `RealSense` |
| **Robotics** | `ROS2` `MAVLink` |
| **Embedded / Edge AI** | `NVIDIA Jetson` `TensorRT` `STM32` |
| **Development** | `Linux` `Docker` `Git` `GitHub` |

---

## 🔗 Projects

| Project | Area | Repository |
|---|---|:---:|
| Structural Stability Physics AI | Multi-View Vision / Physical Reasoning | [GitHub](https://github.com/qewr1234/dacon-structural-stability-ai) |
| Dead Pixel Detector | Sensor / Image Processing | [GitHub](https://github.com/qewr1234/dead-pixel-detector) |
| Leader-Follower Drone | Robotics / Edge AI | [GitHub](https://github.com/qewr1234/drone-swarm-detection) |
| Lightweight VLA | Physical AI / Edge AI | [GitHub](https://github.com/qewr1234/smolvla-fast-lite) |
| KSL Recognition | Multimodal AI | [GitHub](https://github.com/qewr1234/ksl-recognition) |
| POSTECH OIBC Solar | Machine Learning | [GitHub](https://github.com/qewr1234/postech-oibc-solar) |
| LG Aimers 7th | Time-Series ML | [GitHub](https://github.com/qewr1234/LG-Aimers-7th) |
| Hecto AI Challenge | Computer Vision | [GitHub](https://github.com/qewr1234/hai-vehicle-classification) |

---

<div align="center">

**Embedded SW × Physical AI × Robotics × Edge AI**

</div>
