# 캐글 타이타닉 생존자 예측

캐글에서 상시 운영중인 타이타닉 생존자 예측 대회

1. 캐글에서 받아온 데이터를 전처리
2. lasso회귀와 randomforestclassfier로 nan값을 예측
3. xgbclassfier, logisticregression, randomforestclassfier, gradientboostingclassfier, svc로 예측 테스트
4. xgb -> 하이퍼 파라미터 튜닝 진행
5. 예측 진행 -> 정확도 0.799
