# Freshness-Guard-Edge-AI-Based-Anomaly-Detection-for-Produce-Quality
Project Overview
This project is a Computer Vision model that detects loss of freshness and spoilage (anomalies) in carrots in real time, with the aim of reducing waste in the food supply chain. The project is optimized to work especially on low-power edge devices.

🛠️ Technical Stack & Implementation
Model: YOLO (You Only Look Once) - For real-time object detection.

Framework: OpenCV & Python.

Core Concept: Anomaly Detection.

Optimization: ReLU activation function is used to prevent gradient vanishing in deep networks and to speed up training.

💡 Key Features for Edge AI
In line with Infineon's PSoC Edge vision, the following features have been focused on:

Inference Speed: The model has been lightweight to achieve high FPS values ​​even on limited hardware resources.

Data Preprocessing: Data from sensors (cameras) is normalized to reduce noise.

Sigmoid/Softmax Integration: Classification is performed using the Softmax layer to determine the probability of freshness in the final layer.

📈 Performance & Results
Accuracy: 90%+ Average Accuracy (mAP).

Real-time Detection: Small spots and softening (signs of spoilage) on carrots are instantly marked as "Anomalies".

🇰🇷 프로젝트 개요 (Project Overview)
프로젝트 명: Edge AI 기반 농산물 신선도 감지 및 이상 탐지 시스템

개요:
이 프로젝트는 푸드 테크와 공급망 관리를 위해 개발된 컴퓨터 비전(Computer Vision) 솔루션입니다. YOLO 모델을 활용하여 당근의 신선도를 실시간으로 분석하고, 부패나 손상 같은 **이상 징후(Anomaly Detection)**를 즉각적으로 감지합니다. 특히 인피니언(Infineon)의 PSoC Edge와 같은 저전력 임베디드 기기에서 효율적으로 작동하도록 최적화하는 데 중점을 두었습니다.

주요 기술 특징:

실시간 탐지: OpenCV와 YOLO를 사용하여 하드웨어 자원이 제한된 환경에서도 높은 FPS를 유지하며 정밀한 탐지가 가능합니다.

딥러닝 최적화: 학습 과정에서 ReLU 활성화 함수를 사용하여 그래디언트 소실 문제를 방지하고 학습 속도를 개선했습니다.

데이터 전처리: 센서(카메라) 데이터를 정규화하여 노이즈를 줄이고 분석 정확도를 높였습니다.

인피니언(Infineon)을 위한 가치:
저는 인피니언의 DEEPCRAFT 도구와 AIoT 아키텍처를 깊이 이해하고 있습니다. 저의 '신선도 판별 모델'은 인피니언의 Edge AI 기술이 실제 산업 현장에서 어떻게 혁신적으로 쓰일 수 있는지 보여주는 좋은 사례가 될 것입니다. 한국어 학습에 대한 열정과 저의 기술적 역량을 바탕으로 분당 오피스 팀에 기여하고 싶습니다.
