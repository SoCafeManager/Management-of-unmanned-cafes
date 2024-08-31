# Unmanned Cafe Management System

이 프로젝트는 무인 카페의 오염물 인식 및 분실물 관리를 위한 통합 솔루션을 개발하는 것을 목표로 하고 있습니다. 이 시스템은 라즈베리 파이와 같은 경량 하드웨어를 활용하여 비용 효율적인 AI 솔루션을 제공합니다.

<div align="center">

<div>
    <a href="https://opencv.org/"><img src="https://img.shields.io/badge/OpenCV-4.5.3-blue.svg" alt="OpenCV"></a>
    <a href="https://github.com/ultralytics/yolov5"><img src="https://img.shields.io/badge/YOLOv5-6.0-orange.svg" alt="YOLOv5"></a>
    <a href="https://flask.palletsprojects.com/"><img src="https://img.shields.io/badge/Flask-2.0.1-green.svg" alt="Flask"></a>
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.9.5-yellow.svg" alt="Python"></a>
</div>
<br>
</div>

## 주요 기능

- **통합 객체 인식**: 카페 내의 오염물과 분실물을 동시에 인식하고 관리
- **실시간 모니터링**: 웹 기반 인터페이스를 통해 실시간으로 카페의 상태를 모니터링
- **맞춤형 AI 모델**: YOLOv5 모델을 활용하여 무인 카페 환경에 최적화된 인식 기능 제공
- **확장성**: 무인 편의점, 주차장 등 다양한 무인 환경으로 확장 가능
- **환경적 가치**: 지속 가능한 개발 목표에 기반한 시스템 설계

## 기술 스택

- Python
- Flask
- OpenCV
- YOLOv5
- Raspberry Pi
- HTML/CSS/JavaScript

## 설치 및 실행 방법

1. **필요 패키지 설치**:
   ```bash
   pip install -r requirements.txt
2. **모델 다운로드**:
YOLOv5 모델 weight 파일을 다운로드하고 프로젝트 디렉토리에 저장합니다.

3. **서버 실행**:

   ```bash
   python detect_flask.py
웹 인터페이스 접속:
웹 브라우저에서 http://127.0.0.1:5000 으로 접속하여 시스템을 이용합니다.