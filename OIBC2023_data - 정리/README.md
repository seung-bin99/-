# 주최
H ENERGY, POSTECH 오픈 이노베이션 빅데이터 센터, 포스텍 미래도시연구센터

# 배경 및 해결책
- 기 개발된 태양광 발전 예측 모델5개는 서로 다른 특성을 가지고 있어 시간대별 성능 예측에 장단점이 있음
- 이러한 다양한 예측 모델의 특성을 이해하고 활용하여 예측 성능을 향상시킬 수 있는 앙상블 기법을 개발하고자 함

# Process
- EDA
- 가을 계절변수 생성
- 11월 12일 입찰 : 가을 데이터 기준으로 시간대 별 5개 모델의 가중치 부여후 합으로 최종 예측값 선정
- 11월 13일 입찰 : 가을 데이터 기준으로 random forest모델을 optuna 사용해 하이퍼파라미터 설정한 뒤 학습후 예측
- 11월 14일 입찰 : 가을 데이터 기준으로 random forest, xgboost 모델을 optuna 사용해 하이퍼파라미터 설정한 뒤 학습후 예측
- 11월 15일 입찰 : 가을 데이터 기준으로 xgboost + random forest 소프트 보팅 앙상블 모델로 학습후 예측
- 강수량 고려한 가을변수 생성
- 11월 16일 입찰 : 강수량 기상을 고려해 강수량이 있는 9~12월 시간대별 Linear Regression 모델로 학습 후 예측

# 발전량 입찰 그래프
![image](https://github.com/seung-bin99/project/assets/153293674/4bc86eb4-e7a6-497d-b63a-25df706455ec)

# 순위
![image](https://github.com/seung-bin99/project/assets/153293674/cf9f8a8d-37db-4868-b8ca-f5ca42a5b01a)
