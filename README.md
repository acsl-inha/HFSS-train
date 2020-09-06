# HFSS-train

## Train 목적
주어진 table.xlsx의 데이터는 # of turns, permitivity(surface), LS/LW, SEP, permitivity(subsidence), OD, HFSS 로 이루어져있다.
이에 HFSS 이외의 6개의 feature로 HFSS를 표현하는 모델을 구축하고자 한다.

## 모델 구현
총 세가지 모델을 규정했으며, 각 모델은 다음을 가정한다.

### (log) model
<img src="../res_img/mod0.JPG" width="40%">

### (log + first order) model
<img src="../res_img/mod1.JPG" width="40%">

### (log + first order + second order) model
<img src="../res_img/mod2.JPG" width="40%">

