# Customer-age-group-Prediction
> 고객 성별 및 연령대 예측 머신러닝 대회

## Data
L사의 고객 거래 정보 데이터 

## Description
word2vec과 LGBM 모델을 활용하여 남성20대, 30대, 40대, 여성 20대, 30대, 40대로 분류

## Feature Engineering
고객 거래 데이터의 5개 범주형 변수에 word2vec를 적용하여 새로운 feature 생성 후 합친 후 feeture selection을 통해 유의미한 featuer선택

## Modeling
LGBMClssifier 모델을 Randomsearch 방식으로 hyperparameter튜닝
