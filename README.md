## Entry-Based-Security-System

## Requirements
#### Functional Requirements:
OpenCV module:
<br>●	cascadeClassifier: to detect faces in images using Haar Cascade Frontal Face.
<br>●	videoCapture: to read the output of the camera
<br>●	cvtColor: to convert images to gray
<br>●	imread: to read the images
<br>●	LBPHFaceRecognizer: using LBPH machine learning algorithm to train dataset
<br><br>RandomLightFilter module
<br>●	adding filters to images such as addParallelLights, addSpotLights ...
<br><br>Firebase SDK:
<br>●	Pyrebase: it helps to integrate firebase SDK
<br>●	initializeApp: to establish the connection to firebase
<br>●	Real-time database: to store data and get instant change in project
<br>●	Storage: to store all users videos
<br><br>Crontab
<br>●	it’s an operating system function that helps in application scheduling


#### Non-Functional Requirements
●	Videos have to be less than and equal to 10sec and recorded in mobile with vertical alignment
<br>●	Model update daily at 9 pm means new user recognize after 9 pm
<br>●	All capture images deleted after train the model
<br>●	mobile minSDk=29 to install the app
<br>●	Model takes 10min to train 
<br>●	Notification used First-Come-First-Serve basis to grant access
<br>●	Raspberry Pi with Wifi, 1Gb ram, webcam

## Queries/Feedback:
- [Devansh Kaushik](https://www.linkedin.com/in/devansh-kaushik-b5912b174/)
- [Deepak Kumar](https://www.linkedin.com/in/deepak-kumar-548122168/)
- [Diwakar Srivastava](https://github.com/Diwakar012)
