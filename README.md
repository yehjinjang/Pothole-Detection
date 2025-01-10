# Pothoel Dectection Project 

## 📖 Overview
이 프로젝트는 컴퓨터 비전과 딥러닝 기술을 활용하여 도로의 포트홀을 감지하는 시스템을 개발하는 것을 목표로 했습니다. 정확한 포트홀 감지를 통해 도로 안전을 향상시키는 것을 목적으로 합니다.

---

## 🗓️ Period & Team
- **진행 기간:** 2023년 9월 ~ 2023년 12월 (3개월)
- **팀 구성:** DLE 2명

---

## 🛠️ Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)  ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white) 
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) 

---

## 🧑‍💻 Key task
1. **💡 데이터 준비**
   - 도로 이미지 데이터를 수집하고 포트홀 영역에 대해 바운딩 박스를 설정하여 라벨링을 진행하였습니다

2. **🧠 모델 개발**
   - 포트홀 감지를 위한 CNN 기반의 객체 감지 모델을 구현하였습니다
   - 성능 최적화를 위해 MobileNet, YOLO와 같은 사전 학습된 모델을 실험적으로 사용하였습니다

3. **📊 모델 학습 및 평가**
   - TensorFlow와 Keras를 이용하여 라벨링된 데이터를 기반으로 모델을 학습시켰습니다
   - Precision, Recall, F1-score와 같은 지표를 활용하여 모델 성능을 평가하였습니다

4. **📺 실시간 감지**
   - OpenCV와 통합하여 실시간 영상 스트림에서 포트홀 감지가 가능하도록 구현하였습니다

---

## 🌟 Retrospective 
- **기술적 성장:** 객체 감지 모델의 설계 및 구현, 머신러닝과 실시간 영상 처리의 통합 경험을 쌓았습니다.
