# 주최
데이콘

# 배경
- 실제 비즈니스 환경에서 발생하는 데이터를 분석하여 기업 성장과 고객 만족을 도모할 수 있는 전략 개발
  
# 설명
- 비즈니스 환경에서 파악할 수 있는 KPI(ex. MAU, CLV 등)를 도출해 이를 기반으로 KPI를 향상시키기 위한  아이디어 제시

# 기여도
- 5인 진행 (허승빈, 류준호, 안성익, 서현빈, 임한나)
- 허승빈 : 팀장 / 데이터 전처리 / 지역별 배송 지연율 KPI 선정에 대한 분석 및 솔루션 개발, RFM 기법 적용한 고객 분석 / 제안서 작성
- 류준호 : 데이터 전처리 / 지역별 배송 지연율 KPI 선정에 대한 분석 및 EDA
- 안성익 & 서현빈 : 데이터 전처리 / RFM 분석 코드 통합 및 EDA 기반 솔루션 제안서 작성
- 임한나 : 데이터 전처리 / 시간대 별 제품 카테고리 AOV(평균 주문 가치) POWER BI 보고서 작성

# 요약 아키텍처
![image](https://github.com/user-attachments/assets/743b732c-7675-4163-85ba-f0b3a232c987)

# Process
- 브라질 커머스 기업의 제품 구매 / 제품 만족도 / 배송 시간 / 배송 위치 데이터 전처리 및 고객 ID 기준으로 결합
- CRISP 기법을 적용해 데이터 상의 문제를 파악하고, 분석하도록 접근함
- 배송 지역, 주문 상태, 수령 시간에 대한 변수 생성하며, 핵심 KPI를 도출할 수 있도록 진행함

## 1. 지역별 배송지연율
- 만족도와 주요 시간 변수에 대한 상관 분석 및 EDA 검증을 통해 배송지연율 변수 생성
- 지역별 고객 만족도 분석으로 첫 번째 KPI 지표 선정 : 지역별 배송지연율

 💡솔루션 : k Means Clustering기법을 적용해 지역별 제품 배송 센터 솔루션 개발

## 2. 핵심 그룹의 매출 비율
- RFM 분석을 적용해 4개의 고객 등급으로 분류 후, 각 등급의 거래금액 분포 파악
- R, F, M 점수 특성을 반영한 고객 세부 그룹화 후, 매출 분포 파악
- 매출에 영향이 큰 고객 그룹별 매출 분포 EDA를 통해 두 번째 KPI 지표 선정 : 핵심 그룹의 매출 비율

 💡솔루션 : 등급별 마케팅 전략 제안

## 3. 시간대별 제품 카테고리 AOV
- 여러 기준 별 AOV 수치 시각화 및 비교
- 제품 수익 분포 EDA를 통해 세 번째 KPI 지표 선정 : 시간대별 제품 카테고리 AOV(평균 주문 가치)

 💡 모니터링 : 해당 KPI POWER BI 시각화
       솔루션 : 시간대별 전략

# 역할 세부 내용
1. 가설 5개 설정
2. 만족도와 주요 시간 변수에 대한 상관 분석 및 EDA를 통해 가설 검증 및 배송지연율 변수 생성
3. 배송지연율에 대한 추가 가설 검증
4. 지역별 고객 만족도 분석으로 KPI 지표 선정 : 지역별 배송지연율
5. 첫 번째 KPI 솔루션 : k Means Clustering을 적용해 지역별 제품 배송 센터 솔루션 개발
6. RFM 분석을 적용해 4개의 고객 등급으로 세분화 후, EDA를 통해 가설 검증
7. 두 번째 KPI 솔루션 핵심 그룹의 매출 비율에 대한 등급별 마케팅 전략 제안

# 분석과정
![만족도<->배송기간 상관분석](https://github.com/user-attachments/assets/14ccb49b-5432-43b2-81e4-96b825a8c408)
![지역 배송기간 EDA](https://github.com/user-attachments/assets/b1ec18fc-303f-4241-b4d1-41b5c2879d20)
![만족도<->배송지연율 EDA](https://github.com/user-attachments/assets/7f895d7e-3d17-45e7-b9f1-8d888b1f5fd0)
![RFM 분석과정](https://github.com/user-attachments/assets/d250eb56-d388-40ac-a9d2-ab16f57dff5d)


# 결과
![KPI 도출 비즈니스 전략 아이디어 경진대회 수상](https://github.com/user-attachments/assets/386a65d7-e771-4572-8777-5b82916b7cc4)
- 1차 평가 : 투표 결과 리더보드 기준 상위 20개 팀 선정
- 2차 평가 : 1차 평가 통과 팀 데이콘 심사위원단 정성 평가(100%) → 5개 팀 최종 선정
 →  23 팀 중 1차 평가 2위,  2차 평가 1위(최종)

