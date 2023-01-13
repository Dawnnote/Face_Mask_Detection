# README
모든 모델들의 learning rate는 기본 설정값인 0.01, image size는 640입니다.  
YOLOv7은 기본적으로 momentum=0.937, weight_decay=0.0005이 설정되어있습니다. *(weight_decay = L2 penalty)*  
YOLOv8의 optimizer 기본 설정값은 SGD입니다.


<hr/>

1. YOLOv7 (batch size 16, epoch 100) : mAP 0.802
2. YOLOv8 (batch size 16, epoch 50) : mAP 0.752
3. RetinaNet mmdetection(batch size 32, epoch 12) : mAP: 0.685

<hr/>

🎯 가장 높은 성능을 보였던 것은 **YOLOv7 (batch size 16, epoch 100, lr 0.01, imgsize 640 ...)** mAP 0.802  
전이학습시 가중치를 계속 변경하면서 하지 못한 이유는 한번의 학습에 시간이 너무 오래 걸리기 때문
기본적으로 2stage 1stage 의 시간 차이도 상당히 컸으며 정확도 문제 또한 크게 나지 않다고 생각함
최신 트렌드는 1stage가 맞다고 생각함 
