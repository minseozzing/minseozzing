# 🛒 카터가든 (Carter Garden)

> LiDAR SLAM 자율주행과 YOLO 사람 추종이 결합된 스마트 쇼핑카트 + 실시간 웹 관제 시스템

`2026.01 ~ 2026.02` · `팀 6인` · **Frontend & Vision 담당**

<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white"/> <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square"/> <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/> <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white"/>

## 주요 작업

- ROS2 토픽을 Flask 소켓 브릿지로 받아 WebSocket으로 직접 스트리밍, 폴링 지연 없는 실시간 로봇 모니터링 대시보드 구현
- Jetson Orin Nano(4GB RAM)에서 YOLOv8 추론을 TensorRT FP16 + 해상도 축소로 8FPS → 25FPS(**3배**)로 끌어올려 실시간 추종 확보
- 코사인 유사도 기반 중복 필터링으로 주인 등록 시 360도 균등 데이터 수집 보장

🔗 [Live Demo](https://self-driving-shopping-cart.pages.dev/) · [GitHub](https://github.com/minseozzing/Self-Driving-Shopping-Cart)
