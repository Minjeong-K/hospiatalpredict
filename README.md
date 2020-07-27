# hospiatalpredict


## 프로젝트 소개

병원에 대한 회계 데이터를 통해 국내 병원의 개/폐업을 예측하였습니다.
(1) KDD 분석 절차에 따라 진행되며 EDA의 시각화를 통해 데이터의 특징을 파악하였습니다..
(2) 머신러닝 모델 (randomforest, xgboost) 과 PyTorch로 구현한 인공 신경망 모델의 성능을 비교해보았습니다.

## 데이터

Dataset은 한국의 캐글 이라고 불리우는 데이콘(https://dacon.io/) 이라는 사이트에서 획득하였습니다.
* https://dacon.io/competitions/official/9565/overview/

이 데이터의 특징은 float type 64개, object type 4개, int64 type 4개로 구성되어 있습니다. 또한, shape는 row=301개 column = 58개로 구성되어 있습니다. 
이 데이터는 회계 데이터로 주로 구성되어 있습니다.

## reference

- 파이토치 첫걸음 책 참고
- 핸즈온 머신러닝 책 참고
- 파이토치 첫걸음 실습 코드 참고

## team

김영민 - 인천대학교 경제학과

강민정 - 인천대학교 수학과
