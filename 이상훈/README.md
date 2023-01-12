2. 아래 질문에 답변 작성하기 (성능 개선 과정에 대해 자유롭게 작성 가능)
      Q1) 어떤 옵티마이저, 로스 함수를 사용했는지?
       옵티마이저 : SGD, 
      Q2) 처음 시도했던 Network Architecture는 어떤 종류인지?
      
      Q3) 이후 시도해봤던 Network 들은 무엇인지?
      
      Q4) 과대적합을 피하기 위해 했던 작업들은 무엇인지?
      
      Q5) 중요 하이퍼파라미터 어떻게 설정했는지? 이유?
           (배치사이즈(batch size), 에폭(epoch), 학습률(learning rate) 등)
      
      batch size = 4, epoch = 10, optim.SGD(params, lr=0.01,momentum=0.9, weight_decay=0.0005)
           
2-1. 추가로 그동안 학습했던 모델별 하이퍼파라미터와 성능 간략히 적어주시면 더 좋습니다!
      
      1.FastRCNN = optim.SGD(params, lr=0.01,momentum=0.9, weight_decay=0.0005), epoch = 10 = Epoch loss: 0.138
