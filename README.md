![header](https://capsule-render.vercel.app/api?type=venom&color=timeAuto&height=200&section=header&text=Welcome%20World!&fontSize=82&animation=scaleIn)

<h1 align="center">Hi 👋, I'm KIM MYOUNG JI</h1>
<p align="center"><b>Robotics & computer vision engineer</b> · camera-based tracking · ROS 2 · NVIDIA Jetson</p>
<p align="center"><b>로봇·컴퓨터 비전 엔지니어</b> · 카메라 기반 추적 · ROS 2 · NVIDIA Jetson</p>

<details>
<summary><b>🇰🇷 한국어 소개 (클릭해서 펼치기)</b></summary>
<br>

카메라로 사람과 물체를 찾아 따라가는 소프트웨어를 만들고, 그 결과로 모터와 로봇을 움직입니다.

- **카메라 기반 검출·추적**: YOLO 모델을 ONNX·TensorRT로 변환해 Jetson에서 실시간으로 돌립니다
- **추적 결과로 하드웨어 제어**: 추적 결과로 모터를 폐루프 제어합니다(PID)
- **ROS 2 로봇 소프트웨어**: C++와 Python으로 개발합니다
- **데이터와 모델**: 라벨링과 COCO 형식 데이터셋 구축(Roboflow), 검출·분할 모델의 파인튜닝과 mAP 비교(YOLO, MMDetection)
- **사람을 따라 하는 로봇팔**: MediaPipe로 사람 자세를 잡고, 역기구학과 움직임 보정을 적용했습니다

**대표 프로젝트**

- [**ros2-over-tailscale**](https://github.com/kimmandy/ros2-over-tailscale): 서로 다른 네트워크에 있는 ROS 2 장비를 Tailscale로 연결하는 설정 도구입니다. 연결을 조용히 망가뜨리는 설정을 점검하고 링크 성능을 측정합니다(PC ↔ Jetson 실측).
- [**pose-mimic-arm**](https://github.com/kimmandy/pose-mimic-arm): 웹캠으로 본 사람의 팔을 거울처럼 따라 하는 시뮬레이션 6축 로봇팔입니다(MediaPipe, 역기구학, RViz2).

</details>

### 🔭 What I work on

- **Detection and tracking from cameras**: YOLO models exported through ONNX and TensorRT to run in real time on Jetson
- **Tracking that moves hardware**: tracking results drive motors in closed loop (PID)
- **ROS 2 robot software** in C++ and Python
- **Data and models**: labeling and COCO-format datasets (Roboflow), plus fine-tuning and mAP comparison of detection and segmentation models (YOLO, MMDetection)
- **A robot arm that follows a person**: pose from MediaPipe, inverse kinematics and motion smoothing

### 📌 Featured projects

| Project | What it does |
|---|---|
| [**ros2-over-tailscale**](https://github.com/kimmandy/ros2-over-tailscale) | Makes ROS 2 discovery work over Tailscale, checks the settings that silently break it, and benchmarks the link (measured PC ↔ Jetson) |
| [**pose-mimic-arm**](https://github.com/kimmandy/pose-mimic-arm) | A simulated 6-axis arm that mirrors your arm from a webcam: MediaPipe, damped least-squares IK, RViz2 |

### 🛠 Skills

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)

**Robotics**<br>
![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)

**Vision & AI**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge&logo=ultralytics&logoColor=white)
![MMDetection](https://img.shields.io/badge/MMDetection-2B5F9E?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=mediapipe&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white)

**Platforms & tools**<br>
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white)

**Also used** (in robot simulation)<br>
![RViz2](https://img.shields.io/badge/RViz2-3A4A6B?style=for-the-badge)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge)

### 📊 Stats

<p>
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=kimmandy&theme=cobalt&show_icons=true&hide_border=true" alt="Kimmandy's GitHub stats"/>
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimmandy&theme=cobalt&layout=compact&hide_border=true" alt="Top languages"/>
  </a>
</p>

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=pmhyang69)](https://solved.ac/pmhyang69/)

### 📫 Contact

[![Email](https://img.shields.io/badge/kmjicontact@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:kmjicontact@naver.com)

<!-- More links you could add later:
![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)
![Blog](https://img.shields.io/badge/Blog-20C997?style=for-the-badge&logo=velog&logoColor=white)
-->

![footer](https://capsule-render.vercel.app/api?type=waving&color=timeAuto&height=100&section=footer)
