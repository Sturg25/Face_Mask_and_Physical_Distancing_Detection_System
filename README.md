# Face Mask and Physical Distancing Detection System Using Computer Vision
A Thesis software that uses Computer Vision to detect individuals who are not wearing their facemasks and those who are not following physical distancing. This project utilizes neural networks and Tensorflow.

### Functionality
Face Mask and Physical Distancing Detection System detects individuals who are not following health protocols such as improper wearing of face masks and not following physical distancing

#### Motivation
This project is developed by the computer science students from the College of Information and Communications Technology in West Visayas State University as a means to aid the prevention of the transmission of COVID-19. 


## System Requirements
##### Software
•	Anaconda for Spyder IDE  <br/>
•	Python 3.8  <br/>
•	TensorFlow 2.3.0  <br/>
•	GPU Drivers  <br/>
1.	Nvidia CUDA 10.1
2.	cuDNN SDK 8.0.4

#### Hardware
•	Operating System (Windows, Mac, Linux)  <br/>
•	Nvidia GPU with minimum 2GB VRAM  <br/>
•	Camera (Webcam, CCTV, Mobile Phone Client)  <br/>

## Installation 
1.	Download and install Anaconda Software which includes Spyder for the IDE and make sure add Anaconda to the PATH environment variable during the installation.

2.	Once installed, create an environment to be used for this project along with Python 3.8 by opening Anaconda Prompt and type `conda create –name fmpdd python=3.8` where FMPDD stands for Face Mask and Physical Distancing Detection. 

3.	Then download the project software in this repository. This repository includes the necessary files for the project software to operate and also the datasets for the training of the face mask detection model.

4.	Once the project software is downloaded and extracted, set the current environment to FMPDD by using the command `conda activate fmpdd` and proceed to install all the required libraries in `requirements.txt` by using the command `pip install -r requirements.txt` inside the project’s directory using Anaconda Prompt.

5.	Download and install the specified GPU drivers;
<br /> •	Nvidia CUDA 10.1:
(https://developer.nvidia.com/cuda-10.1-download-archive-base)
<br /> •	cuDNN SDK 8.0.4: (This requires to sign up an account to access the download link-https://developer.nvidia.com/cudnn-download-survey)
<br /> After downloading CUDA 10.1, add the folder `C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1` as a system variable as shown in the picture below. <br/>
![alt text](https://github.com/Sturg25/Face_Mask_and_Physical_Distancing_Detection_System/blob/main/pictures/PATH.PNG?raw=true)

6. Download the Yolo Weights which is a pre-trained model to detect social distancing (https://pjreddie.com/media/files/yolov3.weights). From the `src` folder, find the folder named `yolo-coco` and paste the downloaded `yolov3.weights` file inside

## Running the Software
Simply run the `main.py` in the `src`folder using Spyder IDE.

### Training Results
Face Mask Model Training Evaluation <br/>
<img src="pictures/Face_Mask_Model_Training_Evaluation.png" width="400"/> <br/>

Training Loss and Accuracy Plot <br/>
<img src="pictures/Training_Loss_and_Accuracy_Plot.png" width="400"/> <br/>

## Outputs
Individuals with masks on <br/>
<img src="pictures/Flora.png" width="500"/>
<img src="pictures/Marriane.png" width="500"/>  <br/>

Individuals with no masks <br/>
<img src="pictures/Hugo.png" width="500"/>
<img src="pictures/Christian.png" width="500"/> <br/>

Multiple individuals with masks on <br/>
<img src="pictures/Christian 2.png" width="500"/>  <br/>

Multiple individuals <br/>
<img src="pictures/People 1.png" width="500"/>
<img src="pictures/People 2.png" width="500"/>


## Developed by

#### 1. ***Hugo Leroy D. Chavez***
#### 2. ***Flora May D. Gicanal***
#### 3. ***Christian T. Sarabia***
#### 4. ***Marianne Therese E. Tunggak***
#### ***Dr. Frank I. Elijorde***
