# 주최
데이콘, 한국에너지공단

# 목적
- 안정적이고 효율적인 에너지 공급을 위해 전력 사용량 예측
- 전력 사용량 예측 시뮬레이션을 통해 효율적인 인공지능 알고리즘 발굴을 목표로 함

# 설명
- 건물정보와 시공간정보를 활용해서 특정 시점의 전력 사용량 예측하는 AI 모델을 개발

# 요약
- 파생변수 생성
- EDA (시계열, 건물, 군집)
- SMAPE(Symmetric Mean Absolute Percentage Error)
- Nested cross validation으로 하이파라미터 탐색
- gradien boost , xgboost, ...
- 건물번호 별 xgboost 모델 생성
- autogluon으로 모델 생성
- xgboost + autogluon 앙상블 후 제출
