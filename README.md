## Deep Learning Image Classification Practice

TensorFlow와 Keras를 활용하여 다양한 이미지 데이터셋을 분류하는 딥러닝 모델 학습 실습 기록입니다.

### 1. 실습 내용

이미지 분류의 기초부터 합성곱 신경망(CNN) 및 전이 학습(Transfer Learning)을 활용한 심화 분류까지 단계별로 수행했습니다.

- **Fashion Classification (의류 분류)**
    - 기본적인 이미지 분류 모델 구조 학습
    - 다양한 의류 아이템(Top, Trouser, Sneaker 등) 10종 다중 분류(Multi-class Classification)
- **Dog vs. Cat Classification (개/고양이 이진 분류)**
    - 합성곱 신경망(CNN)을 활용한 이미지 특징 추출
    - `ImageDataGenerator`를 이용한 데이터 증강(Data Augmentation) 및 이진 분류 실습
- **Car Classification (자동차 기종 분류)**
    - 다양한 자동차 모델 이미지 데이터셋 처리
    - 대용량 이미지 데이터에 최적화된 모델 설계 및 성능 최적화(수업 후 결과 반영)

### 2. Tech Stack

- **Language**: Python
- **Framework**: TensorFlow 2.x, Keras
- **Library**: NumPy, Matplotlib, Pandas
- **Concepts**: CNN, Data Augmentation, Dropout, Batch Normalization

### 3. 실습 파일 구성

- `딥러닝-패션분류.ipynb`: 다중 분류 기초 모델링
- `딥러닝-개고양이분류-수업후.ipynb`: CNN 기반 이진 분류 및 성능 최적화
- `딥러닝-자동차분류-수업후.ipynb`: 복잡한 이미지 데이터셋 분류 실습

### 4. 주요 학습 포인트

- 모델의 과적합(Overfitting) 방지를 위한 Dropout 및 EarlyStopping 적용
- 실제 이미지 데이터를 딥러닝 모델이 학습 가능한 형태로 변환하는 전처리 과정 이해
- 학습 결과(Accuracy, Loss) 시각화를 통한 모델 성능 분석 및 피드백
