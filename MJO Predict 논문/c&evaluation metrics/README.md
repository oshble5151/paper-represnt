# MJO 기술 평가는 종종 실시간 다변량 MJO(RMM) 지수를 사용하여 수행됩니다.

# RMM 지수는 적도 평균 OLR과 지역 바람의 결합 영역의 경험적 직교 함수(EOFs)와 관련된 기본 구성요소이다.

# 현재 연구에서 재예보의 RMM 지수는 다음의 두 가지 차이를 제외하고 고트샬크 외 연구진(2010)과 V17에 기술된 방법에 따라 도출된다.

# 투영에 필요한 선행 결합 EOF 쌍은 WH04에서 사전 계산된 결합 EOF 대신 ERA-중간 바람에서 얻는다.

# 또 다른 차이점은 기후학이 정의되는 방식이다

# V17에서 기후학은 목표 연도를 제외하고 공통 기간과 동일한 요일과 월에 초기화되는 재예보를 평균화하여 교차 검증된 방식으로 계산됩니다.


![image](https://user-images.githubusercontent.com/73323188/132273816-76d8d211-1812-4280-9838-e95a51503eed.png)
### A0 - 관측된 MJO 진폭
### Am = 예측된 MJO 진폭
### covariability 공분산 관계

![image](https://user-images.githubusercontent.com/73323188/132274237-d3c2bb18-f563-4eb4-8a4c-419c46279463.png)
### RMM space에서의 관측된 그리고 예측된 MJO 위상

### 여기서 O1(t)와 O2(t)는 시간 t에서 관측된 RMM1 및 RMM2 지수이며, M1(t, t)과 M2(t, t)는 각각 리드 타임 t가 t인 재예측치이다.


# 본연구에서 사용된 중요 metrics BCOR이다

# BCOR 이변량 이상 상관 계수(BCOR)
![image](https://user-images.githubusercontent.com/73323188/132274594-880fe6ae-443d-4d83-af93-3d3813445df6.png)

## 이전 연구에 따라 BCOR가 0.5보다 낮아질 때(예: Rashid et al. 2011) 각 모델의 MJO 예측 기술은 예측 리드 타임으로 결정된다.

## 이 임계값의 선택은 다소 임의적이므로 0.7과 같은 다른 임계값도 민감도 실험에서 고려됩니다.


# BMSE 이변량 평균제곱 오차  bivariate-mean-squared error
![image](https://user-images.githubusercontent.com/73323188/132276187-b0fb12a5-ef3b-4f63-a282-8086670745ac.png)

# RMSE < 루트 2는  일반적으로 예측 스킬을 결정하는데 사용된다.

# 따라서 BMSE는 아래와 같이 진폭-오류 구성요소인 BMSea와 위상-오류 구성요소인 BMSep로 분해할 수 있습니다.
![image](https://user-images.githubusercontent.com/73323188/132277422-78795559-4d45-434b-86cd-89ca2c9a0091.png)

![image](https://user-images.githubusercontent.com/73323188/132277577-0741c8aa-4c55-4b34-ab70-823bc22ec8a9.png)

# 아래 나온 것처럼 BMSEa는 기본적으로 평균 제곱 진폭 오차[Eq. (13)]와 동일합니다.

# BMSP는 MJO 위상 오류뿐만 아니라 관측 및 예측 MJO 진폭에 의해 가중치가 결정된다는 점에 유의하십시오.

# 예측 리드 타임에 따라 MJO 진폭이 감소하기 때문에 모든 재예보에 해당하는 증가 BMSEp는 주로 MJO 위상 오차(표시되지 않음)로 설명됩니다.

# 이 분해를 통해 MJO 진폭과 위상 오차가 명확하게 구분되지는 않지만, 그래도 전체 모델 오차를 진폭 의존적 오차와 위상 의존적 오차로 정성적으로 귀속시킬 수 있습니다. 


## relative 렐러티브 
## arbitrary 알버트렐리 임의적인
## derive 목 전+목
## cross-validated 교차 타당한 상관관계 계수
## indices 인디시즈 index 복수 
## index 인덱스  
## empirical 임피리클 경험에 의한 실증적인
## orthogonal 올터거널 직각, 직교의 

### 1) 색인 , 지수
### 2) 색인을 달다 
## empirical orthogonal functions (EOFs) 경험직교함수
## derived 디라이브드 유래된 파생된 

# except for ~을 제외하고 
# except 전치사 접속사 ~을 제외하고
