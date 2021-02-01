# 다음 값 예측 애플리케이션
[![](https://img.shields.io/badge/category-Web%20application-orange)](https://github.com/lgm1007/LineRegressionOnClient)
### 선형 회귀를 이용한 다음 값 예측 애플리케이션

<br/>
Tensorflow.js의 선형 회귀를 응용하여 사용자의 입력값 간 규칙을 학습하여 다음 값을 예측하는 웹 애플리케이션 프로젝트<br/>

[프로젝트](https://predict2regression.netlify.app) 페이지에서 실제로 이용해보세요!

#### Tool

1. HTML 5
2. CSS
3. Tensorflow.js

## Table of Contents

- [Default Page](#Default-Page)
- [Add Input](#Add-Input)
- [Execute Predict](#Execute-Predict)
- [Helped](#Helped)

## Default Page

![](https://i.imgur.com/L4LD8U6.jpg)

사이트에 접속했을 때(애플리케이션 실행하여 접속할 때) 보이는 기본 페이지 모습 

비어있는 텍스트 박스에 입력값을 입력하고, 훈련 횟수와 결과값의 개수를 지정할 수 있다 

## Add Input

![](https://i.imgur.com/tHz3NMG.jpg)

숫자 추가 버튼을 클릭하면 입력값을 여러 개 입력받을 수 있도록 Input Box가 추가된다 

## Execute Predict

| 값 입력                              | 예측 시작                            | 결과값 출력                          |
| ------------------------------------ | ------------------------------------ | ------------------------------------ |
| ![](https://i.imgur.com/MKSiIoC.jpg) | ![](https://i.imgur.com/PmDTeNa.jpg) | ![](https://i.imgur.com/GRX20p1.jpg) |

1. 예측에 필요한 입력값 (ex. 일정 주기의 주식 주가, 연속적인 함수 값 등), 훈련 횟수 (훈련 횟수가 많을 수록 예측값이 더욱 정확하게 출력되지만 어느 정도 이상일 경우 일정한 훈련 효율을 보인다), 원하는 결과값의 개수를 입력한다.
2. 예측 시작 버튼을 클릭하면 Tensorflow 모델이 입력값 간의 규칙을 훈련하고, 진행 상황 부분에서 입력한 훈련 횟수만큼 훈련의 진행 상황을 알 수 있다.
3. 훈련이 종료되면 훈련된 모델이 입력값 다음 예측 값들을 출력한다. 

## Helped

[Tensorflow.js-Guide](https://www.tensorflow.org/js/guide)