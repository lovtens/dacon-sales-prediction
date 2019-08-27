# sales-prediction
Dacon mission
Dacon Mission 9 펀다 상점 매출 예측 경진대회, 2019.7.11 ~ 2019.8.30


### fbprophet
- facebook prophet
- negative data 제거
- sampling
- trend


### lstm
- keras
- negative data 제거
- sampling
- seq2seq

### arima
- statsmodels ARIMA
- negative data 제거
- sampling

### 제출결과


- 8월 24일

using  | option   | Score
-----  | -------- | -------
arima | 1.0 | 1,599,452
arima | 1.3 | 1,220,402
arima | 1.5 | 1,086,564

- 8월 25일

using  | option   | Score
-----  | -------- | -------
arima | 1.65 | 1,080,924
arima | 1.8 | 1,130,274


- 8월 26일  

2주6개 예측합

using  | option         | Score
------- | --------------- | -------
prophet | 2W6PCPS0.05+ | 985,656
prophet | 2W6PCPS0.5+  | 943,433
prophet | 2W6PCPS0.050 | 950,163


- 8월 27일  

지수함수로 감소, 상하한값 두고 logistic regression

using  | option         | Score
------- | --------------- | -------
prophet | 2W6P,CPS0.05exp,logistic | 927,546
prophet | 2W6P,CPS0.5exp,logistic  | 1,002,118


