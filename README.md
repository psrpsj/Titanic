# Titanic - Machine Learning from Disaster
Titanic from Kaggle
## 1. Project Overview
  - 목표
    - 승객 생존여부 예측(1: Not Survived, 0: Survived)
  - 모델
    - Extra Tree Classifier, Random Forest, Catboost등 다양한 분류 모델 실험

## 2. Code Structure
``` text
├── dataset
|   ├── train.csv
|   └── test.csv 
└── titanic.ipynb
```

## 3. Detail 
  - Preprocess 
    - EDA를 통한 데이터 특성에 맞는 전처리 진행(Scaling, Correlation을 통한 결측치 제거 등)
  - Model
    - AutoML을 최적의 모델을 k-Fold를 이용하여 교차검증 한 후, 모델을 학습시킴(제출모델: Extra Tree Classifier)
  - 최종성적
    - Public Score: 0.78708
