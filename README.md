# Titanic Survival Prediction 🛳️
먼저 Age의 이상치를 제거하고 가장 영향이 높을거같은 'Pclass', 'Sex', 'Age', 'Fare'를 기준으로 학습하였다.
train 데이터를 나누어서 Age랑 Fare의 범위가 넓으니 정규화를 하였다.
그뒤 모델들중 가장 Accuracy가 큰 RandomForest를 선택하였다.(Accuracy:0.8364)


## 📂 프로젝트 구조
- `train.csv`: 학습 데이터
- `test.csv`: 테스트 데이터 (예측 대상)
- `submission.csv`: 제출용 예측 결과


## ⚙️ 사용 모델
- RandomForestClassifier
- StandardScaler로 Age 정규화




