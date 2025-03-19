```table-of-contents
title: 
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 0 # Include headings from the specified level
maxLevel: 0 # Include headings up to the specified level
includeLinks: true # Make headings clickable
hideWhenEmpty: false # Hide TOC if no headings are found
debugInConsole: false # Print debug info in Obsidian console
```


# AI 모델의 종류

## 언어 모델 (Language Model)
- 앞 뒤 단어의 확률값을 계산해서 추정
- 모든 언어를 벡터화(숫자화)해서 언어의 의미를 파악하고 출력
### NLP (Natural Language Processing)
- 자연어를 처리하는 전체 과정 및 기술
#### NLU (Natural Language Understanding)
- 자연어를 이해하고 판단하는 과정 및 기술
#### NLG (Natural Language Generation)
- 적절한 자연어 답변을 생성하는 과정 및 기술

## 지식그래프 모델 (Knowledge Graph)
- 개별 객체간의 연관성 관계를 통해서 추론과 유추
- 관련된 정보를 모두 연관 그래프화

## 트리 모델
### 의사결정 트리
- 트리 구조로 이루어진 분류 및 회귀 모델
- 단순, 직관, 해석 가능성 높음 => 많은 분야에서 활용
- 데이터 특성에 따라 과적합 문제가 발생할 수 있어 주의 필요
### 랜덤 포레스트 모델
- 다수의 의사결정 트리를 앙상블하여 성능을 향상시킨 모델
- 분류, 회귀, 군집 등 다양한 문제에 적용 가능
- 과적합 문제를 해결하고 일반화 성능 우수
- 복잡한 데이터셋에서 강력한 성능
### 응용 분야
- 금융, 의료, 마케딩 등 다양한 분야에서 활용
- 결과의 해석이 중요한 경우에 특히 유용
- ex. 고객 세분화, 질병 진단, 신용 평가 등에 널리 사용

## SVM(Support Vector Machine)
### 원리
- 데이터 간의 최대 마진을 찾아 선형 분류
- 고차원 특징 공간에서 선형 분류기 학습을 통해 복잡한 문제도 해결가능

### 특징
- SVM은 소량의 데이터에서도 효과적으로 작동
- 고차원 데이터에 강점
- 추가 기법을 사용하면 복잡한 분류문제 가능

### 응용 분야
- 텍스트 분류, 이미지 인식, 생물정보학 등 다양한 분야에서 활용
- 특히 패턴 인식과 이상 탐지 문제에 뛰어난 성능

## KNN (K-최근접 이웃) 알고리즘 모델
### 원리
- 입력 데이터와 가장 유사한 K개의 이웃을 찾아 분류
- 단순하지만 효과적
- 주로 분류 문제에 사용
### 특징
- 구현이 간단
- 새로운 데이터에 대해 빠르게 예측 가능
- 데이터의 분포와 특성에 따라 성능이 크게 영향 받음
- 대규모 데이터셋에서는 계산 비용이 높아짐

### 응용 분야
- 추천 시스템, 패턴 인식, 이상 탐지 등 다양한 분야에서 활용
- 특히 데이터의 지역적 구조가 중요한 문제에서 효과적으로 사용

# AI 신경망 기술

-  다층 퍼셉트론(Multilayer Perceptron) = AI 신경망
##