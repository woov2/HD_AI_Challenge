# HD 현대 AI Challenge
2023-HD-AI-Challenge-Competition

<br/>

## 1. 배경 & 목적
<예선>
- 코로나19 이후 물류 정체로 인해 다수의 항만에서 선박 대기 시간이 길어지고, 이로 인한 물류 지연이 화두가 되고 있음.
- 특히 전 세계 물동량의 85%를 차지하는 해운 물류 분야에서 항만 정체는 큰 문제로 인식되고 있는 상황임.
- 접안(배를 육지에 대는 것;Berthing) 전에 선박이 해상에 정박(해상에 닻을 바다 밑바닥에 내려놓고 운항을 멈추는 것;Anchorage)하는 시간을 대기시간으로 정의하고, 선박의 제원 및 운항 정보를 활용하여 산출된 항차(voyage; 선박의 여정) 데이터를 활용하여 항만 內 선박의 대기 시간을 예측하는 AI 알고리즘을 개발

<본선>
- 건설/기계 센서 데이터를 활요해 작업 중량을 예측하는 AI 알고리즘 개발

<br/>

## 2. 주최/주관 & 참가 대상 & 성과

- 주최/주관: HD한국조선해양 AI Center / DACON
- 참가 대상: 국내외 대학생/대학원생 / HD현대 그룹사 임직원
- 성과: 예선 1위 / 본선 2위 / 최종 우수상 수상

<br/>

## 3. 대회 기간
<예선>
- 제출마감: 2023년 10월 30일
- 코드 평가 마감 및 최종순위 발표: 2023년 11월 06일

<본선>
- 제출마감 : 2023년 11월 09일
- 코드 평가 마감 및 최종순위 발표: 2023년 11월 09일

<br/>

## 4. 내용

<예선>
- 국제 무역량 / BDI 지수 등 외부 데이터를 활용
- 선박의 제원 및 운항 정보를 통해 산출된 항차(voyage; 선박의 여정) 데이터를 활용하여 Feature Engineering
- LGBM / XGB를 사용하여 Modeling 진행
- 날짜 별 기상정보를 활용하여 Target Logic Algorithm 사용

<본선>

- Sensor Data Transformation을 통한 ML Modeling
- Shift / rolling 기법을 활용한 Feature Engineering
- Tweedie loss function을 적용한 Modeling
- LGBM / Catboost를 사용해 Modeling
- Geometric mean Ensemble 사용

<br/>

## 5. Process

### ch.1 Feature Engineering

<예선>

- Categoryical Feature Combination
- Holiday Feature
- Date Feature
- Label Encoding

<본선>

- Data Architecture 변형
- Shift / Rolling을 활용한 Time Series Feature

---

### ch.2 Preprocessing

<예선>

- 외부 데이터 전처리
- NAN 전처리

<본선>

- Time Series to Table Transform

---

### ch.3 Modeling

<예선>

- LGBM
- XGB

<본선>

- LGBM
- Catboost

---

### ch.4 Ensemble

<예선>

- Weighted Ensemble(LGBM 0.8 / XGB 0.2)

<본선>

- Weighted / Geometric Ensemble

<br/>

## 6. 참고자료

[HD현대 AI Challenge 사이트](https://dacon.io/competitions/official/236158/overview/description)
