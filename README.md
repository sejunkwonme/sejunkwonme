# 권세준

**Marketing Manager**
대한민국, 서울 | sejunkwon@outlook.com |  | 

***

## Experience

**Marketing Manager at Creative Agency**
New York, NY | August 2019 – Present | 4 years

* Led a team of 5 marketing specialists to develop and execute digital marketing campaigns.
* Increased brand awareness for clients through targeted advertising, resulting in a 40% increase in overall engagement.
* Managed social media accounts, content calendars, and performance metrics to ensure consistency across platforms.
* Spearheaded marketing efforts for product launches, achieving a 20% increase in sales within the first quarter.

**Digital Marketing Specialist at Growth Solutions**
New York, NY | May 2016 – July 2019 | 3 years 2 months

* Developed content for email marketing campaigns that achieved a 35% open rate.
* Managed Google Ads campaigns, optimizing keywords and budgets for maximum ROI.
* Analyzed website traffic using Google Analytics and prepared reports to adjust marketing strategies.

***

## Projects

**Opencl을 이용한 Vggnet-16 추론 최적화 - (TeamProject)**

* ai 모델을 런타임에서 실행하지 않고 Opencl kernel 함수를 직접 작성하여 convolution연산을 병렬처리  
* Im2col 기법으로 중복된 연산을 2D 메모리 공간에 투영, 이후 GEMM 기법으로 연산 최적화  
* relu, softmax 등의 프레임워크 연산을 C언어 레벨에서 배치 단위로 처리할 수 있도록 직접 구현  
 
**Pytorch를 이용한 Yolov1 구현 - (PersonalProject)**

* ai 모델 플랫폼에서 제공되는 모델을 사용하지 않고 직접 Paper를 보고 모델의 구조, 손실함수, metric 등을 구현
* 그리드 셀 내부와 이미지 전체에 대한 좌표 스케일링이 필요하므로 모든 배치와 i, j 번째 셀에 대해 좌표변환을 수행할 수 있는 함수 구현
* IoU(Intersection over Union), NMS(Non-Maximum-suppression) 그리고 mAP(mean-Average-Precisoin) 등의 메트릭, 후처리 기능을 배치처리로 수행할 수 있도록 구현
* 위의 매트릭 후처리는 for문 없이 torch.Tensor의 연산으로 병렬처리 됨 (NMS는 배치처리가 불가하므로 이미지 한장씩 처리)

***

## 기술스택

**프로그래밍 언어:** C/C++, Python  
**라이브러리:** OpenCV, OpenCL, Cuda, Gstreamer  
**프레임워크:** Qt, Pytorch  

***

## 학력사항

**B.S. in Data Science**  
Sejong University, 2020 – 2025  

**High School**  
선린인터넷고등학교, 2014 - 2016
