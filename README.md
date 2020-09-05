# HFSS-train

## Train 목적
주어진 table.xlsx의 데이터는 # of turns, permitivity(surface), LS/LW, SEP, permitivity(subsidence), OD, HFSS 로 이루어져있다.
이에 HFSS 이외의 6개의 feature로 HFSS를 표현하는 모델을 구축하고자 한다.

## Data preprocessing
주어진 table.xlsx의 데이터는 아래 그림과 같이 동일한 앞부분 feature에 대해 다른 뒤따라 오는 feature들이 표현되어 있는데, 이때 각각의 값으로 주어진 것이 아닌 큰 묶음 형식으로 표현되어 있다.
