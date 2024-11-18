<img src="https://img.shields.io/badge/nvidia-76B900?logo=nvidia&logoColor=black" style="border-radius:10px">

# Nvidia AI Specialist Certification
✅ OverView of the Project


- Opening background information

- General description of the current project

- Proposed idea for enhancements to the project

- Value and significance of this project

- Current limitations

- Literature review
<br/>

## Title
✅ Hanger detection<br/>

## Opening background information
✅ Hanger plays an important role in organizing clothes neatly at a clothing store or at home.
But how convenient would it be if there was a system that automatically detects hangers for efficient organization?
For example, if store employees don't have to manually count or organize hangers, this not only saves time, but also reduces confusion that may arise when customers choose and place products.

## General description of the current project
✅ This project utilizes object detection models such as YOLOv5 to identify hangers.
  We are currently in the process of collecting data and training a model to accurately detect hangers and distinguish them from surrounding objects.
  The goal is to collect hanger images from various angles and backgrounds so that the model can perform more general hanger detection and automatically determine the location and number of hangers so that it can be used in various application environments.
<br/>

## Proposed Idea for Enhancements to the Project
- Automate tasks and improve efficiency<br/>
The location, status, and number of hangers can be automatically detected and managed, reducing manpower input and greatly increasing management efficiency.<br/>

- Various application possibilities<br/>
This system is highly flexible as it can be used in a variety of environments, including clothing stores, rental services, and smart home environments. It can be easily adjusted to suit each environment, providing a customized solution.<br/>

- Real-time monitoring possible<br/>
The status of hangers can be checked in real time and changes can be detected and responded quickly, allowing managers to take necessary action immediately.
<br/>

## Value and signifiance of the project
✅ This project can automatically manage hanger status in real-world applications such as store management or rental services, contributing to reducing manpower burden. 
In particular, management efficiency can be improved by providing the ability to quickly detect and take action when a customer does not return a rented item or places it in the wrong location. 
Additionally, this technology can be used in a smart home environment and provides convenience by automatically checking necessary information at home.
<br/>

## Current Limitations
- Lack of data diversity<br/>
It is necessary to collect data covering a variety of hangers and backgrounds, but model performance may deteriorate due to data biased toward a specific environment.<br/>
- Real-time performance<br/>
In some cases, real-time processing required for real-world applications is difficult, and to solve this problem, it may be necessary to use a lightweight model or improve hardware performance.<br/>

## Literature Review
- A variety of learning data about hangers, image recognition, object detection, etc. are needed.<br/>

## How to acquire images
- Acquire videos and images by directly filming hangers in homes, factories, etc. with a camera.
![hanger640px](https://github.com/user-attachments/assets/86c4c1bd-53a0-40b6-a5c9-b2e4a6701a52)

- If you want to acquire additional images of various hangers, you can do so by searching.
<br/>
1. In order to learn at a resolution of 640 x 640, videos and images are cut to fit 640 x 640.<br/>
https://online-video-cutter.com/ko/resize-video<br/>
You can easily cut it through their site. 

![hanger1](https://github.com/user-attachments/assets/c06db853-debd-4cd4-ad7b-c97af388f359)
<br/>
<br/>
2. DarkLabel
Extract the collected video into an image in DarkLabel.<br/>
https://www.zaivhub.com/ko/yolov5<br/>
After downloading the DarkLabel program and data.yaml file through this site, you can use it to convert collected videos and images into labeled images.
<br/>
<br/>
3. Open the darklabel.yml file with notepad.
![hanger2](https://github.com/user-attachments/assets/bfa23ef4-8d95-48ad-a19a-15a537bf0b31)
<br/>
<br/>
4. Add classes.
![hanger3](https://github.com/user-attachments/assets/f145c1a0-38e0-4b51-aeba-33a0fab0de96)
<br/>
<br/>
5. Add format9.
![hanger4](https://github.com/user-attachments/assets/fa0421ed-32db-4429-919b-aea30539bc62)
<br/>
<br/>
6. Run DarkLabel.exe and apply the created class.
![hanger5](https://github.com/user-attachments/assets/004ffdb1-3071-4b49-bc87-92a9f9bd718d)
<br/>
<br/>
7. Click the **Open Video** button to open the video, and press the **as Images** button to save the frame image.
![hanger6](https://github.com/user-attachments/assets/989c5b67-43f2-401d-937a-23d5a953aa83)
<br/>
<br/>
8. Extract the collected videos and images as images and labels from DarkLabel.
![hanger7](https://github.com/user-attachments/assets/aecc4b16-47fb-4c6b-8665-7e8e0a1b9c3c)
<br/>
<br/>
## Edit Data.yaml file and download data model
1. Edit the data.yml file obtained when downloading Darklabels in the yolov5-master folder.
![hanger8](https://github.com/user-attachments/assets/13cf6fd0-6703-4284-af73-c3a1d45ef21e)
<br/>
<br/>
2. Download the yolov5n.pt file through the link below.<br/>
https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5n.pt
<br/>
<br/>
3. This is the result obtained through the above processes.

![hanger9](https://github.com/user-attachments/assets/39ae98cd-6666-4f72-89d7-b61bccffc201)
<br/>
<br/>
## Write code using Google Colaboratory.

1.Integrates with Google Drive.
![colaboratory1](https://github.com/user-attachments/assets/d1171595-b8d1-443f-a4dc-88f75d9187e4)
<br/>
<br/>
2. Install yolov5.

![colaboratory2](https://github.com/user-attachments/assets/c3daf345-13d3-4d1e-b158-3bdd1c479484)
<br/>
<br/>
3. Create a train folder and a valid folder.
![스크린샷 2024-11-11 235918](https://github.com/user-attachments/assets/4e7af51b-e78b-4c75-9362-d41163d85789)
<br/>
<br/>
4. Move the file according to the path.
<br/>
<br/>
Location of images folder and labels folder
<br/>
![11](https://github.com/user-attachments/assets/1496cfc0-2a9a-4ec6-bc3d-c1d2e6cd4153)
<br/>
data.yaml file location
<br/>
![12](https://github.com/user-attachments/assets/75189fb0-d82e-4d70-b05e-7edc992c2f0c)
<br/>
yolov5n.pt model location
<br/>
![13](https://github.com/user-attachments/assets/bfac26b3-ca43-4713-abf3-ae9ca272fa08)
<br/>
<br/>
<br/>
5. Generate verification data.
<br/>
![14](https://github.com/user-attachments/assets/860ee778-a751-4ecd-ac74-a359d8033e40)
<br/>
<br/>
python train.py --img 640 --batch 16 --epochs 50 --data .\data\data.yaml --weights yolov5s.pt
<br/>
<br/>
## Start learning
1. Add the necessary libraries.
![15](https://github.com/user-attachments/assets/f3376f82-7e16-4cc0-a627-e28fd5472efe)
<br/>
<br/>
2. Start learning by executing the command below.
<br/>
![16](https://github.com/user-attachments/assets/82cfb491-e364-41ea-9be4-f785b44d4136)
<br/>
<br/>
## Check learning outcomes
Learning Spin Label Result<br/>
First training dataset<br/>
<img src= "https://github.com/user-attachments/assets/dfd919e0-7812-43dd-94fc-0716447848c9" width="450" height="450"/> 
<img src= "https://github.com/user-attachments/assets/5834e370-9288-465b-a91a-e79516376321" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/5cf34557-6705-4c28-b66b-3601928fb02d" width="450" height="450"/> 
<img src= "https://github.com/user-attachments/assets/e2abd56a-d28c-4781-a31d-e20c09f64d5f" width="450" height="450"/>
<br/>
<br/>
Second training dataset<br/>
<img src= "https://github.com/user-attachments/assets/63835b0a-a90f-480d-a939-bae4a40f35ad" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/c0f0448b-95d9-4efb-84c8-e1bed22860cc" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/08d15ef2-ebc7-4238-b730-d35dff152770" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/12a6cb17-a388-4f08-b2bf-75ffd56ceb1c" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/8515caa2-34e9-4818-9212-55de4231c025" width="450" height="450"/>



<img src= "https://github.com/user-attachments/assets/35c4fd26-ce42-4695-9d35-5767e7fdaef3" width="900" height="450"/>
      
<img src= "https://github.com/user-attachments/assets/d59a479d-3e04-48c3-b95a-887e991fb71e" width="450" height="450"/>
<img src= "https://github.com/user-attachments/assets/f03543dc-eadf-43b9-9264-fa8914144b9d" width="450" height="450"/>
     
<img src= "https://github.com/user-attachments/assets/9663cccd-1638-4426-b9a9-12876ca90d31" width="900" height="450"/>

## Verification of learning outcomes
1. You can verify using the command below.<br/>
python detect.py --weight runs/train/exp/weights/best.pt --source [Path to image to test] --img 640 --conf 0.8<br/>
![17](https://github.com/user-attachments/assets/e84ff179-7b00-49b2-8650-cfc50e7fcf6e)
<br/>

The data below are videos and images that tested hanger recognition by learning the data set.
[https://drive.google.com/drive/u/1/folders/1Dszc60V5G3CHSQ0zd0aF-G_srDMLxVWs](https://drive.google.com/drive/u/1/folders/1njvKxfqWYTfXqmK4b9JIsXS1LjuBdEmH)

![hanger_fin (1)](https://github.com/user-attachments/assets/1f22ce21-5f82-4d8e-8339-05a683ee51fa)
![hanger_fac (2)](https://github.com/user-attachments/assets/0bb43d5f-9277-4c31-94a3-1ff576b42d0e)
![test2 (1) (1)](https://github.com/user-attachments/assets/ed9adf82-e91c-4142-817e-320ff9439227)
![unnamed (1)](https://github.com/user-attachments/assets/d381516f-18b4-4052-afdb-673cdfedfa1c)

<br/><br/>
Below is a link to the data set.<br/>
[![Google Drive](https://img.shields.io/badge/googledrive-4285F4?logo=Google%20Drive&logoColor=yellow)](https://drive.google.com/drive/u/1/folders/1nidFfqTUAautHjpQHn3mh8XRgNCAxoPy) [HangerDataSet1 - Google Drive](https://drive.google.com/drive/u/1/folders/1nidFfqTUAautHjpQHn3mh8XRgNCAxoPy)

[![Google Drive](https://img.shields.io/badge/googledrive-4285F4?logo=Google%20Drive&logoColor=yellow)](https://drive.google.com/drive/u/1/folders/1PDb7UvKxC7rHQvV2npQWZAbZaD9qr1pZ) [HangerDataSet2 - Google Drive](https://drive.google.com/drive/u/1/folders/1PDb7UvKxC7rHQvV2npQWZAbZaD9qr1pZ)
<br/>
<br/>

