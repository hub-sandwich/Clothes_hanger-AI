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
가정옷걸이 감지 코드<br/>
Hanger detection<br/>

## Opening background information
✅ 배경정보<br/>
의류 매장에서나 가정에서 깔끔하게 옷을 정리하는 데 중요한 역할을 하는 것이 바로 옷걸이인데요, 하지만 효율적인 정리를 위해 옷걸이를 자동으로 감지해주는 시스템이 있다면 얼마나 편리할까요? 
예를 들어, 매장 직원들이 수작업으로 옷걸이 수를 확인하거나 정리할 필요가 없다면 시간을 절약할 수 있을 뿐 아니라, 손님들이 제품을 고르고 놓는 과정에서 발생할 수 있는 혼란도 줄일 수 있습니다.
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
![hanger3](https://github.com/user-attachments/assets/f145c1a0-38e0-4b51-aeba-33a0fab0de96)
<br/>
<br/>
5. format9를 추가합니다.
![hanger4](https://github.com/user-attachments/assets/fa0421ed-32db-4429-919b-aea30539bc62)
<br/>
<br/>
6. DarkLabel.exe를 실행시키고, 생성한 클래스를 적용합니다.
![hanger5](https://github.com/user-attachments/assets/004ffdb1-3071-4b49-bc87-92a9f9bd718d)
<br/>
<br/>
7. **Open Video** 버튼을 눌러 영상을 열고, 프레임 이미지를 저장하기 위해 **as Images** 버튼을 눌러 저장합니다.
![hanger6](https://github.com/user-attachments/assets/989c5b67-43f2-401d-937a-23d5a953aa83)
<br/>
<br/>
8. 수집한 영상 및 이미지를 DarkLabel 에서 image와 label로 추출합니다.
![hanger7](https://github.com/user-attachments/assets/aecc4b16-47fb-4c6b-8665-7e8e0a1b9c3c)
<br/>
<br/>
## Data.yaml 파일 수정 및 데이터 모델 다운
1. yolov5-master 폴더에 Darklabels를 다운받을 때 얻은 data.yml파일을 수정해줍니다.
![hanger8](https://github.com/user-attachments/assets/13cf6fd0-6703-4284-af73-c3a1d45ef21e)
<br/>
<br/>
2. 아래 링크를 통해 yolov5n.pt 파일을 다운받습니다.<br/>
https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5n.pt
<br/>
<br/>
3. 위 과정들을 통해 얻은 결과물입니다.

![hanger9](https://github.com/user-attachments/assets/39ae98cd-6666-4f72-89d7-b61bccffc201)
<br/>
<br/>
## Google Colaboratory 를 사용하여 코드를 작성해줍니다.

1.구글 드라이브와 연동합니다.
![colaboratory1](https://github.com/user-attachments/assets/d1171595-b8d1-443f-a4dc-88f75d9187e4)
<br/>
<br/>
2. yolov5를 설치합니다.

![colaboratory2](https://github.com/user-attachments/assets/c3daf345-13d3-4d1e-b158-3bdd1c479484)
<br/>
<br/>
3. train 폴더와 valid 폴더를 생성합니다.
![스크린샷 2024-11-11 235918](https://github.com/user-attachments/assets/4e7af51b-e78b-4c75-9362-d41163d85789)
<br/>
<br/>
4. 경로에 맞게 파일을 옮겨줍니다.
<br/>
<br/>
images 폴더와 labels 폴더 위치
<br/>
![11](https://github.com/user-attachments/assets/1496cfc0-2a9a-4ec6-bc3d-c1d2e6cd4153)
<br/>
data.yaml 파일 위치
<br/>
![12](https://github.com/user-attachments/assets/75189fb0-d82e-4d70-b05e-7edc992c2f0c)
<br/>
yolov5n.pt 모델 위치
<br/>
![13](https://github.com/user-attachments/assets/bfac26b3-ca43-4713-abf3-ae9ca272fa08)
<br/>
<br/>
<br/>
5. 검증 데이터를 생성합니다.
<br/>
![14](https://github.com/user-attachments/assets/860ee778-a751-4ecd-ac74-a359d8033e40)
<br/>
<br/>
python train.py --img 640 --batch 16 --epochs 50 --data .\data\data.yaml --weights yolov5s.pt
<br/>
<br/>
## 학습 시작
1.필요한 라이브러리를 추가합니다.
![15](https://github.com/user-attachments/assets/f3376f82-7e16-4cc0-a627-e28fd5472efe)
<br/>
<br/>
2.아래 명령어 실행 시 학습을 시작합니다.
<br/>
![16](https://github.com/user-attachments/assets/82cfb491-e364-41ea-9be4-f785b44d4136)
<br/>
<br/>
## 학습 결과물 확인
학습 돌린 라벨 결과물 train_batch
    
<img src= "https://github.com/user-attachments/assets/dfd919e0-7812-43dd-94fc-0716447848c9" width="450" height="450"/> 
<img src= "https://github.com/user-attachments/assets/5834e370-9288-465b-a91a-e79516376321" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/5cf34557-6705-4c28-b66b-3601928fb02d" width="450" height="450"/> 
<img src= "https://github.com/user-attachments/assets/e2abd56a-d28c-4781-a31d-e20c09f64d5f" width="450" height="450"/>
            
<img src= "https://github.com/user-attachments/assets/35c4fd26-ce42-4695-9d35-5767e7fdaef3" width="900" height="450"/>
      
<img src= "https://github.com/user-attachments/assets/d59a479d-3e04-48c3-b95a-887e991fb71e" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/f03543dc-eadf-43b9-9264-fa8914144b9d" width="450" height="450"/>
     
<img src= "https://github.com/user-attachments/assets/9663cccd-1638-4426-b9a9-12876ca90d31" width="900" height="450"/>

## 학습 결과물 검증
1. 아래 명령어를 통해 검증을 할 수 있습니다.<br/>
python detect.py --weight runs/train/exp/weights/best.pt --source [테스트할 이미지의 경로] --img 640 --conf 0.8<br/>
![17](https://github.com/user-attachments/assets/e84ff179-7b00-49b2-8650-cfc50e7fcf6e)
<br/>

[![Google Drive](https://img.shields.io/badge/googledrive-4285F4?logo=Google%20Drive&logoColor=yellow)](https://drive.google.com/drive/u/1/folders/1nidFfqTUAautHjpQHn3mh8XRgNCAxoPy) [Hanger - Google Drive](https://drive.google.com/drive/u/1/folders/1nidFfqTUAautHjpQHn3mh8XRgNCAxoPy)
<br/>
<br/>

