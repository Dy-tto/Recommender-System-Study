# Chap4. Content\-Based Recommender System

## 4.2 Basic Components of Content-Based Systems
- Preprocessing and feature extraction
  + 키워드 기반 벡터 공간 표현으로 변환
- Content\-Based learning of user profiles
  + 과거 이력을 기반으로 사용자별 모델을 구성해 예측
  + 사용자 피드백과 아이템 속성을 함께 사용
- Filtering and recommendation
  + 학습된 모델을 이용해 추천, 효율적이여야함
## 4.3 Preprocessing and Feature Extraction
- Feature Extraction
  + 일반적으로 기본 데이터에서 키워드 추출
  + 가중치 설정 필요
- Feature Representation and Cleaning
  + Stop\-word Removal
  + Stemming
  + Phrase extraction
- Collectiong User Likes and Dislikes
  + Ratings
  + Implicit feedback
  + Text opinions
  + Cases
- Supervised Feature Selection and Weighting
  + Gini Index
  + Entropy
  + 카이제곱
  + Normalized Deviation
  + Feature Weighting
## 4.4 Learning User Profiles and Filtering
- Nearest Neighbor Classification
  ![image](https://user-images.githubusercontent.com/59719632/179327208-34410095-0a12-4aa9-8da4-223ffcf7573a.png)
- Coneections with Case\-Based Recommender Systems
- Baysed Classifier
- Rule\-based Classifiers
  + 주어진 활성 사용자에 대한 모든 규칙을 마이닝
- Regression\-Based Models
  + 다양한 유형의 평가에 사용 가능
## 4.5 Content-Based VS Collaborative Recommendations
- Advantages
  + 신규 사용자가 아닌 이상 새 아이템을 다른 아이템과 비교해 의미 있는 추천이 가능
  + 피처 관점에서 아이템을 설명할 수 있음
  + off\-the\-shelf text classfiers에 사용 가능
- Disadvantages
  + 기존과 유사한 아이템을 찾는 경향이 있음
  + 새로운 사용자에 대해 cold\-start 문제가 발생 할 수 있음

