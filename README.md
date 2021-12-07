# 통계 분석


## Description

Simple Data를 활용해 통계 분석을 수행하였다.

  
<br/>

## 신뢰 구간(Confidence Interval)

### Description

* NHANES 데이터를 활용.
* 흡연율과 BMI 수치에 대한 신뢰구간을 측정하고 통계적 유의성을 분석.

### Confidence Interval

* [CI_nhanes](https://github.com/pcw789/statistics_python/blob/main/Confidence_Interval.ipynb)

### 분석

* 남성과 여성의 흡연자 비율 95% 신뢰구간 측정
* 남성과 여성의 흡연자 비율 차이 측정
* 남성과 여성의 BMI 수치 95% 신뢰구간 측정
* 남성과 여성의 BMI 수치 차이 측정

  
<br/>

## 가설 검정(Hypothesis Test)

### Description

* 가상의 예시 데이터, nhanes 데이터 활용.
* 귀무가설과 대립가설을 설정하고 p값 측정 및 유의성 분석.

### Hypothesis Test

* [Hypothesis_test](https://github.com/pcw789/statistics_python/blob/main/Hypothesis_testing.ipynb)

### 분석

* 남성과 여성의 흡연자 비율 95% 신뢰구간 측정
* 남성과 여성의 흡연자 비율 차이 측정
* 남성과 여성의 BMI 수치 95% 신뢰구간 측정
* 남성과 여성의 BMI 수치 차이 측정

  
<br/>

## P-value Vs Power

### Description

* 가상의 데이터를 활용해 Power의 변화에 따라 P-value의 분포가 어떻게 변하는지 확인.

### 

* [P-value_Power](https://github.com/pcw789/statistics_python/blob/main/P-value%20vs%20Power.ipynb)

### 분석

* Power는 true effect가 존재할 때, 귀무가설을 올바르게 기각할 확률.(1-베타)
* Power가 커질수록 작은 값을 가지는 P-value의 분포가 많아진다.
* Power가 굉장히 클 경우, 대부분의 P-value는 0.01보다 작은 값을 가진다.
  * 이 경우, Significance Level(알파)를 0.05로 하면 어떻게 될까?
    - p-value가 0.045가 나오면, p<0.05 이기 때문에 null hypothesis를 기각한다.
    - 그런데, 대립가설 쪽에서도 이 수치는 매우 희박한 확률을 가진다. (대부분의 p-value가 0.01보다 작기 때문에 0.045는 관측하기 어렵다.)
    - paradox
  * 그렇기 때문에, 높은 Power를 가지는 가설을 설정할때는 낮은 Significance Level을 가지도록 설계해야한다.

