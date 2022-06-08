# Project - Jetson Nano를 탑재한 드론을 이용한 장애물 인식

## 목표
- Jetson Nano를 탑재한 드론이 기동 중 장애물(박스)를 마주쳤을 때 충돌을 방지하기 위해서 정지한다.

### 방법
1. Jetson Nano에 YOLO v5를 탑재해 Object Detecting을 진행한다.
2. Object Detecting을 통해 탐지한 장애물에 대해서 드론이 장애물로 인식하고 기동을 멈춘다.
