# 권세준

**Machine Vision Engineer** | 대한민국, 서울 | sejunkwon@outlook.com |  

***

## Experience

**경험을 쌓고 함께할 회사를 찾는 중입니다.**

***

## Projects

[**Opencl을 이용한 Vggnet-16 추론 최적화 - (TeamProject)**](https://github.com/sejunkwonme/Vgg16)

* CNN Classifier 모델을 런타임에서 실행하지 않고 GEMM Opencl kernel 함수를 직접 작성하여 convolution연산을 GPU 에서 병렬처리  
* Im2col 기법으로 중복된 연산을 2D 메모리 공간에 투영하여 인수끼리 곱하고 더하는 연산을 한번의 행렬곱으로 연산 최적화  
* relu, softmax 등의 기계학습 프레임워크 연산을 C언어 레벨에서 배치 단위로 처리할 수 있도록 포인터와 스트라이드를 통해 직접 구현  
 
[**Pytorch를 이용한 Yolov1 구현 - (PersonalProject)**](https://github.com/sejunkwonme/Yolov1)

* ultralytics등의 플랫폼에서 제공되는 모델을 사용하지 않고 직접 Paper를 보고 모델의 구조, 손실함수, 데이터 처리 로직 등을 구현
* 그리드 셀 내부와 이미지 전체에 대한 좌표 스케일링이 필요하므로 모든 배치와 i, j 번째 셀에 대해 좌표변환을 수행할 수 있는 함수 구현
* IoU(Intersection over Union), NMS(Non-Maximum-suppression) 등 데이터 전처리, 후처리 기능을 배치처리로 수행할 수 있도록 구현
* for문을 최대한 배제하여 torch.Tensor의 연산으로 병렬처리 됨 (NMS는 배치처리가 불가능)

[**Qt 프레임워크를 이용한 Computer Vision GUI Application 개발 - (PersonalProject)**](https://github.com/sejunkwonme/CVS)

* 컴퓨터에 연결된 웹캠의 프레임을 받아와 GUI에 렌더링 하는 기능 구현, Qt의 object-worker 멀티스레딩 모델로 구현하여 시작, 중지 가능, 다른 기능을 얹어 확장 가능
* Pytorch로 학습한 기계학습 모델 추론 기능을 ONNX Runtime api를 이용해 구현
* CUDA를 이용하여 추론 레이어 중 일부를 GPU Architecture 와 메모리 용량에 최적화되게 custon layer를 구현하여 둥작할수 있는 기능 구현 (예정)

***

## Tech Stack

**프로그래밍 언어:** C/C++, Python  

**라이브러리 Api:** OpenCV, OpenCL, Cuda, Gstreamer, ONNX Runtime  

**프레임워크:** CMake, Qt, Pytorch  

***

## Biographical profile

**B.S. in Data Science**  
Sejong University, 2020 – 2024  

**병장 만기전역**  
대한민국 공군 작전정보통신단 정보체계병, 2017 - 2019  

**High School**  
선린인터넷고등학교, 2014 - 2017  
