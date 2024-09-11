# CNN (Convolutional Neural Network)

- 16\. cloth_mnist 데이터 셋 다중 분류
- 17\. cats and dogs 데이터 셋 이진 분류
---
- 데이터의 공간 정보를 활용하기 위한 NN 모델
- 필터의 수 -> feature map의 개수
- 필터 사이즈 -> 보통 3 or 5; 이러면 feature map의 사이즈도 줄긴 함
- pooling -> 보통 max pooling을 쓰는데 그러면 feature map의 사이즈 반절
    - 홀수인 경우 내림 처리
- flatten -> 데이터를 1차원으로 변경
