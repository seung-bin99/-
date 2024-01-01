# 주최
데이콘, 대구광역시, 한국자동차연구원, ...

# 배경
- 이동수단의 발달에 따라 다양한 유형의 교통사고들이 계속 발생
- 사고의 원인을 규명하고 사고율을 낮추기 위해, 시공간 정보로부터 사고위험도(ECLO)를 예측하는 AI 알고리즘 발굴
  
# 설명
- 사고 발생 시간, 공간 등의 정보를 활용하여 사고위험도(ECLO)를 예측하는 AI 모델 개발

# Process
- 도시, 구, 동에 따라 각 데이터 결합
- 다중대치(MICE)로 결측치 대체
- Target Encoding
- RMSLE 평가식 정의
- Kfold, random split 로 train data 분리
- MLP, transformer 모델 설계후 optuna를 사용해 최적하이파라미터 탐색후 학습후 예측
- automl통한 모델 학습후 예측
- MLP + automl 결과 앙상블 후 제출

# 기여도
- 본 대회는 모든 작업을 혼자서 수행

# 후기
- 데이터에 대한 구체적인 조사 후 진행했으면 feature engineering을 통해 더 좋은 결과를 낼 수 있었을 것이라 생각함
  
# 결과
![image](https://github.com/seung-bin99/project/assets/153293674/3fcedb1f-ad42-42c3-bf84-956209af5bcc)
