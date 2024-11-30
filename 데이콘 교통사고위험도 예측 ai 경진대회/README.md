# 주최
데이콘, 대구광역시, 한국자동차연구원 등

# 배경
- 이동수단의 발달에 따라 다양한 유형의 교통사고들이 계속 발생
- 사고의 원인을 규명하고 사고율을 낮추기 위해, 시공간 정보로부터 사고위험도(ECLO)를 예측하는 AI 알고리즘 발굴
  
# 설명
- 사고 발생 시간, 공간 등의 정보를 활용하여 사고위험도(ECLO)를 예측하는 AI 모델 개발

# 기여도
- 본 대회는 모든 작업을 혼자서 수행

# Process
- 도시, 구, 동에 따라 각 데이터 결합
- IterativeImputer로 결측치 대체
- Target Encoding
- RMSLE 평가식 정의
- Kfold 교차검증 사용 5개 폴드(4개 폴드 train 데이터 / 1개 폴드 valid 데이터
- MLP, transformer 딥러닝 모델에 optuna를 사용해 하이파라미터 최적화한 후, 학습 및 예측
- automl통한 모델 학습 및 예측
- MLP + automl 결과 앙상블 후 제출
  
# 결과
- 28th / 942team
![image](https://github.com/user-attachments/assets/dfa4d138-8609-4e11-9e2f-05aaf1f59501)

