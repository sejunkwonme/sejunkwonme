# 권세준
**Machine Vision Engineer** | 대한민국, 서울 | sejunkwon@outlook.com |  
***

## Experience
**경험을 쌓고 함께할 회사를 찾는 중입니다.**
***

## Projects
[**Opencl을 이용한 Vggnet-16 추론 최적화 - (TeamProject)**](https://github.com/sejunkwonme/Vgg16)

* Vgg16 CNN Classifier 모델을 런타임에서 실행하지 않고 GEMM Opencl kernel 함수를 직접 작성하여 convolution연산을 GPU 에서 병렬처리  
* Explicit Im2col 기법으로 순차 CNN 연산을 2D 메모리 공간에 투영하여 한번의 행렬곱으로 연산 최적화  
* Relu, Softmax 등의 기계학습 프레임워크 연산을 C언어 레벨에서 배치 단위로 처리할 수 있도록 포인터와 스트라이드를 통해 직접 구현  
 
[**Pytorch를 이용한 Yolov1 구현 - (PersonalProject)**](https://github.com/sejunkwonme/Yolov1)

* Joseph Redmon의 Paper와 다른 여러 오픈소스 구현체들을 참고하여 모델의 구조, 손실함수, 데이터 처리 로직 등을 구현
* 그리드 셀 내부에 대한 좌표 스케일링과 이미지 전체에 대한 것이 다르므로 좌표변환을 수행할 수 있는 함수 구현
* IoU(Intersection over Union), NMS(Non-Maximum-suppression), mAP(Mean Average Precision) 등 데이터 전처리, 후처리, 그리고 평가 메트릭 기능을 수행할 수 있도록 구현
* 대부분 torch.Tensor의 연산으로 배치처리 됨

[**Qt 프레임워크를 이용한 Computer Vision GUI TestBed 개발 - (PersonalProject)**](https://github.com/sejunkwonme/CVS)

* 웹캠의 프레임을 받아와 GUI에 렌더링 하는 기능 구현, Qt의 object-worker 멀티스레딩 모델로 구현하여 캡처와 추론 시작, 중지 가능 구현 및 성능측정 가능
* Pytorch로 학습한 기계학습 모델 추론 기능을 ONNX Runtime api를 이용해 구현
* CUDA를 이용하여 캡처-추론 파이프라인에서 데이터 전처리 단계를 병렬처리 커널함수로 작성하여 기존의 CPU 기반 순차 Opencv 이미지 처리 함수를 대체
* 최적화를 통해 Edge Device에서 30fps의 프레임 생성 시간에 맞추어 작동할 수 있도록 개선 (예정)
***

## Tech Stack
**프로그래밍 언어:** C/C++, Python  

**라이브러리 Api:** OpenCV, OpenCL, Cuda, Gstreamer, ONNX Runtime  

**프레임워크:** CMake, Qt, Pytorch, Torchvision  

***
## Biographical profile

**B.S. in Data Science**  
Sejong University, 2020 – 2024  

**병장 만기전역**  
대한민국 공군 작전정보통신단 정보체계병, 2017 - 2019  

**High School**  
선린인터넷고등학교, 2014 - 2017  

***

## License
**운전면허 1종 보통**  
**정보처리기능사**
