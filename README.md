# Drowsiness-detection
Drowsiness Detection Using CNN and HAAR Cascade Models.
 In this system, the image of face of the driver is taken through the camera on regular intervals and examine the changes that happen in the eye.
 These images will be processed through an algorithm which will compare them with the dataset of images. If the comparison matches the predefined percentage of match, then drowsiness is detected and alert is sent to driver.

SYSTEM ARCHITECTURE
![image](https://github.com/VishalKGowda/Drowsiness-Detection-Using-OpenCV/assets/55918199/5b1a10ac-dad0-48f7-8d49-326ce4a651a9)


IMPLEMENTATION DETAILS:
Step 1 – Take image as input from a camera.
Step 2 – Detect the face in the image and create a Region of Interest (ROI).
Step 3 – Detect the eyes from ROI and feed it to the classifier.
Step 4 – Classifier will categorize whether eyes are open or closed.
Step 5 – Calculate score to check whether the person is drowsy.


RESULTS:

![image](https://github.com/VishalKGowda/Drowsiness-Detection-Using-OpenCV/assets/55918199/9d8741ff-3c40-4ade-b764-8fc4b7295af0)
EYES FULL OPEN

![image](https://github.com/VishalKGowda/Drowsiness-Detection-Using-OpenCV/assets/55918199/4d1e6fbd-5b3a-4e0c-93d5-1e2dfd99206d)
EYES HALF OPEN

![image](https://github.com/VishalKGowda/Drowsiness-Detection-Using-OpenCV/assets/55918199/b6a6ec1f-df1b-49e1-a8ea-cb365a2b41ee)
EYES CLOSED

![image](https://github.com/VishalKGowda/Drowsiness-Detection-Using-OpenCV/assets/55918199/755aba9d-6012-4b07-800f-5068043c213c)
EYES CLOSED FOR MORE THAN 5 SECONDS RESULTING IN AN ALARM SOUND RINGING




