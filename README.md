<img src="https://img.shields.io/badge/nvidia-76B900?logo=nvidia&logoColor=black" style="border-radius:10px">

# Nvidia AI Specialist Certification
✅ OverView of the Project

프로젝트 개요

- Opening background information (내 프로젝트의 전반적인 문맥을 위해서 필요!)

- General description of the current project (프 로젝트의 전반적인 설명)

- Proposed idea for enhancements to the project (제안하고 싶은 프로젝트의 강점)

- Value and significance of this project (중요성)

- Current limitations (직면하고 있는 한계)

- Literature review(전반적인 프로젝트의 배경지식 공유를 위해서!)
<br/>

## Title
✅ 주제<br/>
옷걸이 감지<br/>
Hanger detection<br/>

## Opening background information
✅ 배경정보<br/>
이 프로젝트는 물리적 공간에서의 옷걸이 감지를 통해 특정 작업을 자동화하려는 목적으로 시작되었습니다. 
예를 들어, 매장이나 공공장소, 또는 가정에서 옷걸이의 배치를 관리하거나 특정 물건이 걸려 있는지 감지해 상태를 확인하는 데 활용할 수 있습니다. 
최근 컴퓨터 비전과 인공지능 기술의 발전으로 인해 사물 감지와 이미지 인식이 점점 더 일상적으로 활용되고 있으며, 이를 통해 사람의 수고를 줄이고 작업의 정확도를 높이는 것이 가능합니다.
<br/>
***
- This project began with the goal of automating certain tasks through the detection of hangers in a physical space. 
For example, it can be used to manage the placement of hangers in stores, public places, or at home, or to check the status of certain items by detecting whether they are hanging. 
With recent advances in computer vision and artificial intelligence technologies, object detection and image recognition are becoming more and more commonplace, making it possible to reduce human effort and improve task accuracy.
<br/>

## General description of the current project
✅ 프로젝트 전반적인 설명<br/>
이 프로젝트에서는 옷걸이를 특정하기 위해 YOLOv5와 같은 객체 탐지 모델을 활용하고 있습니다.
현재는 옷걸이를 정확히 탐지하고 주변 물체와 구분할 수 있도록 하기 위해 데이터를 수집하고 모델을 학습시키는 단계에 있습니다. 
옷걸이 이미지를 다양한 각도와 배경에서 수집하여 모델이 보다 일반화된 옷걸이 탐지를 수행할 수 있도록 하고, 옷걸이의 위치와 개수 등을 자동으로 파악하여 여러 응용 환경에서 사용할 수 있도록 하는 것이 목표입니다.
<br/>
***
- This project utilizes object detection models such as YOLOv5 to identify hangers.
  We are currently in the process of collecting data and training a model to accurately detect hangers and distinguish them from surrounding objects.
  The goal is to collect hanger images from various angles and backgrounds so that the model can perform more general hanger detection and automatically determine the location and number of hangers so that it can be used in various application environments.
<br/>

## Proposed Idea for Enhancements to the Project
✅ 제안하고 싶은 프로젝트의 강점
- 작업 자동화 및 효율성 향상<br/>
옷걸이의 위치, 상태, 개수 등을 자동으로 감지해 관리할 수 있어 인력 투입을 줄이고 관리 효율을 크게 높일 수 있습니다.<br/>

- 다양한 응용 가능성<br/>
이 시스템은 의류 매장, 대여 서비스, 스마트 홈 환경 등 여러 환경에서 활용 가능해 유연성이 높습니다. 각 환경에 맞게 쉽게 조정할 수 있어 맞춤형 솔루션을 제공합니다.<br/>

- 실시간 모니터링 가능<br/>
실시간으로 옷걸이 상태를 파악하고 변화를 감지하여 빠르게 대응할 수 있어, 관리자가 즉각적으로 필요한 조치를 취할 수 있습니다.
<br/><br/>
***
- Automate tasks and improve efficiency<br/>
The location, status, and number of hangers can be automatically detected and managed, reducing manpower input and greatly increasing management efficiency.<br/>

- Various application possibilities<br/>
This system is highly flexible as it can be used in a variety of environments, including clothing stores, rental services, and smart home environments. It can be easily adjusted to suit each environment, providing a customized solution.<br/>

- Real-time monitoring possible<br/>
The status of hangers can be checked in real time and changes can be detected and responded quickly, allowing managers to take necessary action immediately.
<br/>

## Value and signifiance of the project
✅ 프로젝트의 중요성<br/>
이 프로젝트는 매장 관리나 대여 서비스와 같은 실제 응용 사례에서 옷걸이 상태를 자동으로 관리할 수 있어 인력 부담을 줄이는 데 기여할 수 있습니다. 
특히 고객이 대여한 물품을 반납하지 않거나 잘못된 위치에 배치했을 때 이를 신속히 탐지하고 조치를 취할 수 있는 기능을 제공함으로써 관리 효율을 높일 수 있습니다. 
또한, 이러한 기술을 통해 스마트 홈 환경에서도 활용이 가능하며, 가정에서 필요한 정보를 자동으로 확인할 수 있어 편리성을 제공할 수 있습니다.<br/>
<br/>
***
- This project can automatically manage hanger status in real-world applications such as store management or rental services, contributing to reducing manpower burden. 
In particular, management efficiency can be improved by providing the ability to quickly detect and take action when a customer does not return a rented item or places it in the wrong location. 
Additionally, this technology can be used in a smart home environment and provides convenience by automatically checking necessary information at home.
<br/>

## Current Limitations
✅ 직면하고 있는 한계<br/>
- 데이터 다양성의 부족<br/>
다양한 옷걸이와 배경을 아우르는 데이터 수집이 필요하나, 특정 환경에 치우친 데이터로 인해 모델의 성능이 저하될 수 있습니다.<br/>
- 실시간 성능<br/>
실제 응용에 필요한 실시간 처리가 어려운 경우가 있으며, 이를 해결하기 위해 경량화 모델을 사용하거나 하드웨어 성능을 개선해야 할 수 있습니다.<br/>
***

- Lack of data diversity<br/>
It is necessary to collect data covering a variety of hangers and backgrounds, but model performance may deteriorate due to data biased toward a specific environment.<br/>
- Real-time performance<br/>
In some cases, real-time processing required for real-world applications is difficult, and to solve this problem, it may be necessary to use a lightweight model or improve hardware performance.<br/>

## Literature Review
✅ 문헌 고찰<br/>
옷걸이에 대한 다양한 학습데이터와 이미지인식, 객체탐지등 다양한 이해가 필요합니다.<br/>
<br/>
***
- A variety of learning data about hangers, image recognition, object detection, etc. are needed.<br/>

## 영상 취득 방법
- 가정집, 공장등에 있는 옷걸이를 직접 카메라로 촬영하여 영상 및 이미지를 취득합니다.
![hanger640px](https://github.com/user-attachments/assets/86c4c1bd-53a0-40b6-a5c9-b2e4a6701a52)

- 추가로 다양한 옷걸이에 대한 이미지를 획득하고 싶으면 서칭을 통해 획득합니다.
<br/>
1. 해상도를 640 x 640으로 학습하기 위해 위하여 영상 및 이미지를 640 x 640에 맞게 잘라줍니다.<br/>
https://online-video-cutter.com/ko/resize-video<br/>
해당 사이트를 통해 쉽게 자를 수 있습니다.  

![hanger1](https://github.com/user-attachments/assets/c06db853-debd-4cd4-ad7b-c97af388f359)
<br/>
<br/>
2. DarkLabel
수집한 영상을 DarkLabel 에서 이미지로 추출합니다.<br/>
https://www.zaivhub.com/ko/yolov5<br/>
해당 사이트를 통하여 DarkLabel 프로그램과 data.yaml 파일을 다운 받은 후에 사용하여 수집한 영상 및 이미지에 대해 라벨이 달린 이미지로 변환이 가능합니다.
<br/>
<br/>
3. darklabel.yml 파일을 메모장으로 열어줍니다.
![hanger2](https://github.com/user-attachments/assets/bfa23ef4-8d95-48ad-a19a-15a537bf0b31)
<br/>
<br/>
4. 클래스를 추가합니다.

5. format9를 추가합니다.





















