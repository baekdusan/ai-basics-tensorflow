# Decision Tree, Random Forest
- 펭귄 데이터 셋을 가지고 두가지 학습 모델을 돌려 본다
- 훈련 데이터와 테스트 데이터의 transform 의 차이를 아는 것이 중요.
    - 훈련 데이터만 fit_transform; 검증과 테스트는 fit 할 필요가 없음.
- score를 계산할 때 다중 분류는 average의 파라미터로 'macro'를 사용.