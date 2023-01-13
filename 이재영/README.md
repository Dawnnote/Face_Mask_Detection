# README
모든 모델들의 learning rate는 기본 설정값인 0.01, image size는 640입니다.  
YOLOv7은 기본적으로 momentum=0.937, weight_decay=0.0005이 설정되어있습니다. *(weight_decay = L2 penalty)*  
YOLOv8의 optimizer 기본 설정값은 SGD입니다.

<hr/>

1. YOLOv7 (batch size 16, epoch 50) : mAP 0.46
2. YOLOv7 (이미지의 preprocessing, augmentations 옵션 수정, epoch 100으로 수정) : **mAP 0.73**
3. YOLOv7 (동일 조건에서 Adam optimizer 추가 적용) : mAP 0.53
4. YOLOv8s (batch size 16, epoch 100) : mAP 0.64
5. YOLOv8l (동일 조건에서 epoch 60으로 수정) : **mAP 0.71**

<hr/>

🎯 가장 높은 성능을 보였던 것은 **YOLOv7 (batch size 16, epoch 100, lr 0.01, imgsize 640 ...)** mAP 0.73  
단, YOLOv8x를 써봤다면 더 높은 성능이 나왔을 수도 있겠다는 생각도 들었습니다.
