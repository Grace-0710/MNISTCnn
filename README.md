# MNISTCnn
MNIST데이터를 활용한 CNN 모델 구조 구현

<img width="1445" alt="스크린샷 2023-03-26 오후 6 57 31" src="https://user-images.githubusercontent.com/84004919/227768337-c0a6048d-2d1d-404a-a390-e6d8bd942ad7.png">

<img width="1504" alt="스크린샷 2023-03-26 오후 6 57 41" src="https://user-images.githubusercontent.com/84004919/227768342-0b46bc01-003f-4390-be00-7829ed2e11c9.png">


* torch.nn.Conv2d(
    in_channels, 
    out_channels, 
    kernel_size, 
    stride=1, 
    padding=0, 
    dilation=1, 
    groups=1, 
    bias=True, 
    padding_mode='zeros'
)
<img width="535" alt="스크린샷 2023-03-26 오후 6 56 19" src="https://user-images.githubusercontent.com/84004919/227768246-ba62fb49-86cf-4bb1-8136-1acbdf0ca0dc.png">

* cnn_model.py > ConvolutionalClassification > forward()
<img width="311" alt="스크린샷 2023-03-26 오후 6 59 28" src="https://user-images.githubusercontent.com/84004919/227768408-7297ab4f-2d79-447c-b90f-2c9e3d8df3eb.png">
