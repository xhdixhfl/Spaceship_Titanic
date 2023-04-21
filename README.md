# Spaceship_Titanic 🚀
> kaggle competition 연습용 대회인 spaceship titanic으로 차원이동에 성공여부를 예측함 <br>
> 기간 : 22.11.01 ~ 22.11.25.
<br>

## 프로젝트 소개
**1. 프로젝트 주제**: 우주선 탑승 고객의 차원이동 여부 예측 <br>
**2. 프로젝트 목적**: 머신러닝 교육과정 중 배운 내용을 활용하여, 여러가지 예측 모델을 구현하고자 함 <br>
**3. 기능** : xgboost, stacking ensemble, catboost등의 decision tree기반의 모델등을 활용하고자함

## 담당 역할
**1. 데이터 탐색 및 전처리** <br>
→ anova, 다중공선성 등을 확인하고 필요없는 컬럼과 결측치 등을 제거함 <br>
※ [데이터 탐색을 위한 시각화](https://github.com/xhdixhfl/Spaceship_Titanic/blob/main/bone_%EC%8B%9C%EA%B0%81%ED%99%94.pdf)
**2. 결측치 채우기** <br>
→ cryoSleep(xgboost), homeplanet(랜덤포레스트, xgboost), destination(xgboost) 결측치를 예측모델을 활용하여 채움<br>
※ [결측치 예측](https://github.com/xhdixhfl/Spaceship_Titanic/blob/main/%EC%A0%84%EC%B2%98%EB%A6%AC_CryoSleep%26HomePlanet%26Destination.ipynb)
**3. stacking ensemble 모델 활용**<br>
→ 선형회귀, adaboost, randomforest, xgboost등의 모델들을 요소로 서치그리드,교차검증 등을 사용하며 결과도출 <br>
※ [stacking ensemble](https://github.com/xhdixhfl/Spaceship_Titanic/blob/main/Stacking_Ensemble.ipynb)

## 개발도구


## 발표자료
