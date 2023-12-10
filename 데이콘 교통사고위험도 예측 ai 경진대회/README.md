# 주최
데이콘, 대구광역시, 한국자동차연구원, ...

# 목적
- 안정적이고 효율적인 에너지 공급을 위해 전력 사용량 예측
- 전력 사용량 예측 시뮬레이션을 통해 효율적인 인공지능 알고리즘 발굴을 목표로 함

# 설명
- 건물정보와 시공간정보를 활용해서 특정 시점의 전력 사용량 예측하는 AI 모델을 개발

# 요약
- 도시, 구, 동에 따라 각 데이터 결합
- IterativeImputer 사용한 결측치 처리
- Target Encoding
- RMSLE 평가식 정의
- Kfold, random split 로 train data 분리
- MLP, transformer 모델 설계후 optuna를 사용해 최적하이파라미터 탐색후 학습후 예측
- automl통한 모델 학습후 예측
- MLP + automl 결과 앙상블 후 제출

# 결과
![image](https://github.com/seung-bin99/project/assets/153293674/3fcedb1f-ad42-42c3-bf84-956209af5bcc)
