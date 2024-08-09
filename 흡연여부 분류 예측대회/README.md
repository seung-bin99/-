# 주최
DACON

# 배경
흡연 여부를 분류하는 모델을 개발
신체적 조건과 건강 상태를 나타내는 여러 지표들을 통해 건강과 흡연의 관계 등을 파악가능

# 설명
흡연 여부를 분류하는 AI 알고리즘 개발

# 기여도
- 본 대회는 혼자서 수행

# Process
- EDA 및 시각화
- Isolation Forest 사용한 이상치 처리
- 변수 생성
- 분석 후, 불필요한 변수 제거
- Logistic regression, SVC, Decision Tree, Random Forest, Naive Bayes, Xgb 등 활용해 성능 좋은 모델 확인
- Random Forest, Naive Bayes, Xgb로 소프트보팅 앙상블 방법으로 모델 설계후 예측
  
# 결과
![image](https://github.com/seung-bin99/project/assets/153293674/87974f98-904b-4557-8cf4-6e86dc6075e9)

# 후기
- 파생 변수 생성 및 상관 분석으로 유의미한 변수 추출로 인해 우수한 성과를 낼 수 있었던 것 같음
