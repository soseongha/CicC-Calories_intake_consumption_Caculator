
<div align="center">

# 🍕 CicC 🍕 </br> Calories intake & consumption Caculator
2023 ML project<br><br>
<img src="https://img.shields.io/badge/lanaguage-python-8A2BE2&logo=#512BD4"/>
<img src="https://img.shields.io/badge/using-Colab-8A2BE2"/>

<div align="left">
  
<br><br><br>  
## ❇️ Project Introduction

[CicC: Calories intake & consumption Caculator]는 취한 칼로리를 간편하게 기록하고 개인의 신체 조건에 따른 칼로리
소모량을 계산해 주는 시스템입니다.
<br><br><br><br>

## 📑Data
1. ‘Food Images (Food-101)’, Kaggle, K Scott Mader,
https://www.kaggle.com/datasets/kmader/food41?resource=download
2. 일부 여대생의 활동에너지 소비패턴, 활동계수, 기초대사량 및 에너지 소비량 평가
https://koreascience.kr/article/JAKO201312061568898.pdf
3. physical activity and controlling weight
https://www.k-state.edu/[https://www.k](https://www.k/)[state.edu/paccats/Contents/PA/PDF/Physical Activity and Controlling Weight.pdf](http://state.edu/paccats/Contents/PA/PDF/Physical%20Activity%20and%20Controlling%20Weight.pdf)
4. Calories Burnt Prediction
https://www.kaggle.com/code/pragathiputhran/calories-burnt-prediction/input?select=exercise.csv
5. Calories Burned During Exercise and Activities
https://www.kaggle.com/datasets/aadhavvignesh/calories-burned-during-exercise-and-activities
6. 음식 별 칼로리 섭취량 제공 사이트
[https://www.fatsecret.com](https://www.fatsecret.com/)
<br><br>

## 🔨 Fuction 
- **칼로리 섭취량 계산 model:** OCR로 영양성분표 인식과, DeIT image classification으로 음식 이미지 인식을 통해 사용자가 하루 동안 섭취한 총 칼로리양을 계산

- **칼로리 소모량 계산 model:** 개인의 신체 정보와 운동량을 반영한 칼로리 소모량 데이터를 기반으로 하여 사용자의 칼로리 소모량을 회귀 예측

- **User input에 결과 출력:** 아래 과정에 따라 User의 신체정보, 오늘 먹은 음식의 사진이나 영양성분표, 실행한 운동 등을 입력 시 섭취와 소모, 기초대사량을 고려한 총 칼로리 소모량을 계산함
<br><br>

![CacC2](https://github.com/soseongha/CicC-Calories_intake_consumption_Caculator/assets/79681915/9a710840-6a84-46ab-98dd-3e4b72b09e1b)

