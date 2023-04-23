# Spaceship_Titanic 🚀
> kaggle competition 연습용 대회인 spaceship titanic으로 차원이동한 승객의 성공 여부를 예측함 <br>
> 기간 : 22.11.01 ~ 22.11.25.
<br>

## 프로젝트 소개
**1. 프로젝트 주제**: 우주선 탑승 고객의 차원이동 여부 예측 <br>
**2. 프로젝트 목적**: 머신러닝 교육과정 중 배운 내용을 활용하여, 여러가지 예측 모델을 구현하고자 함 <br>
**3. 기능** : xgboost, stacking ensemble, catboost등의 decision tree기반의 모델등을 활용하고자함
<br>
<br>

## 담당 역할
**1. 데이터 탐색 및 전처리** <br>
→ anova, 다중공선성 등을 확인하고 필요없는 컬럼과 결측치 등을 제거함 <br>
<div align=right>

※ [데이터 탐색을 위한 시각화](https://github.com/xhdixhfl/Spaceship_Titanic/blob/main/bone_%EC%8B%9C%EA%B0%81%ED%99%94.pdf)  </div>
 
**2. 결측치 채우기** <br>
→ cryoSleep(xgboost), homeplanet(랜덤포레스트, xgboost), destination(xgboost) 결측치를 예측모델을 활용하여 채움<br>
<div align=right>

※ [결측치 예측](https://github.com/xhdixhfl/Spaceship_Titanic/blob/main/%EC%A0%84%EC%B2%98%EB%A6%AC_CryoSleep%26HomePlanet%26Destination.ipynb)  </div>

**3. stacking ensemble 모델 활용**<br>
→ 선형회귀, adaboost, randomforest, xgboost등의 모델들을 요소로 서치그리드,교차검증 등을 사용하며 결과도출 <br>
<div align=right>

※ [스태킹앙상블](https://github.com/xhdixhfl/Spaceship_Titanic/blob/main/Stacking_Ensemble.ipynb)  

</div>

## 개발도구 및 언어
<div>
<img src="http://img.shields.io/badge/Jupyter-F37626?style=round&logo=Jupyter&logoColor=white" />
<img src="http://img.shields.io/badge/Python-3776AB?style=round&logo=Python&logoColor=white" />
<img src="http://img.shields.io/badge/microsoftexcel-217346?style=round&logo=microsoftexcel&logoColor=white" />
</div>
<br>

## 모델별 결과
*※ 22년도 11월 25일 기준 결과임을 밝힘 </u>*

#### 1. XGboost  
<div align=center>

![xgb](https://user-images.githubusercontent.com/114147352/233786952-8c81292f-55e0-4b3b-b190-a4a9c72e76c2.png)

</div> <br>

#### 2. Stacking Ensemble  
<div align=center>

![se](https://user-images.githubusercontent.com/114147352/233786914-26b30b61-f15a-4858-b5eb-80b085000d7a.png)

</div> <br>

#### 3. CatBoost
<div align=center>

![cat](https://user-images.githubusercontent.com/114147352/233786904-69a56cc2-9a06-463e-816e-9ae7fb702462.png)

</div> 
