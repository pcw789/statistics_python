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
* Power와 Effect Size, Sample Size, 알파(Type I error)는 서로 얽혀있다.
* Power가 커지기 위해선
  - Effect Size가 크다.
  - Sample size가 크다.
  - 알파가 작다.
* 남성과 여성의 BMI 수치 차이 측정

