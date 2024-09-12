# CNN (Convolutional Neural Network)

- 데이터의 공간 정보를 활용하기 위한 NN 모델
- 필터의 수 -> feature map의 개수
- 필터 사이즈 -> 보통 3 or 5; 이러면 feature map의 사이즈도 줄긴 함
- pooling -> 보통 max pooling을 쓰는데 그러면 feature map의 사이즈 반절
    - 홀수인 경우 내림 처리
- flatten -> 데이터를 1차원으로 변경
---
## Transfer Learning (전이 학습)

- 거대 데이터 셋으로 학습된 모델의 fully connected layer만 용도에 맞게 변경하여 사용하는 방법
- 해당 예제에서는 VGG16을 사용하였음.
---
- 16\. cloth_mnist 데이터 셋 다중 분류
- 17\. cats and dogs 데이터 셋 이진 분류
- 18\. cats and dogs with transfer learning
- 19\. plantvillage 데이터 셋 직접 레이어 쌓기 vs 전이 학습 정확도 비교
    - 해당 실습에서는 early stopping을 사용하여 과적합을 방지하였음.