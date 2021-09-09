
# Python-DeepLearning_DNN_Stduy

## 딥러닝을 이용한 영상 분류 

### 모델 특징 
 * 딥 러닝 라이브러리 중 하나인 케라스 라이브러리를 이용하여 구현.
 * CNN을 이용하여 해당 모델을 구현하였으며, convolution layer와 maxpooloing layer을 교차로 사용.
 * padding은 same을 적용하여 출력 이미지 사이즈가 줄어들지 않고 입력 이미지 사이즈와 동일하게 되도록 설정.
 * activation function은 relu를 적용하였으며, 정확도가 많이 오르지 않아서 dropout의 비율을 높여 정확도를 높이도록 시도.


### 모델 학습 및 실험 결과 

* 최종 모델 성능표 (test data 실험 성능 )

|지표     ||값 |
|---------|---|----|
|Accuracy|Total|74.26%|
|Accuracy|Cat|70.91%|
|Accuracy|Dog|77.61%|
|Loss||0.5336|
|FPS||824.02|
|Model Size||2,370KB|

* 학습 그래프

![캡처](https://user-images.githubusercontent.com/51026066/132628602-3ff11d26-d59a-4756-b0bb-98d1cab563f5.PNG)
