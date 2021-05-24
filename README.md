# RUP

RUP에 탑재되는 model을 훈련하기 위한 repositorie입니다.

[TensorFlow2 Object Detection](https://github.com/tensorflow/models)을 이용하여 object detecion을 수행하였습니다.

TensorFlow2 Object Detection을 수행하기 위한 환경은 Docker를 이용하였고 [docker](https://github.com/hogbal/RUP/tree/master/docker)에서 확인할 수 있습니다.

## 폴더 구조

```sh
├─docker
│  │  README.md
│  ├─tf-latest
│  ├─tf2.5.0rc1
│  ├─tf2.5.0rc2
│  └─tf2.5.0rc3
│
├─preprocessing
│ 
└─tensorflow
   ├─script
   └─object_detection
      └─workspace
         └─training_rup
            ├─annotations
            ├─exported-models
            ├─mobile
            ├─models
            ├─pre-trained-models
            └─predict
```

[exported-models](https://github.com/hogbal/RUP/tree/master/tensorflow/object_detection/workspace/training_rup/exported-models)에서 학습된 모델을 확인할 수 있습니다.
