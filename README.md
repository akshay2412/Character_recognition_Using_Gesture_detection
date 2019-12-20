# Character_recognition_Using_Gesture_detection
In the project “Character_recognition_Using_Gesture_detection” the user will wave in front of the camera i.e make gestures and try to write something in the air . The system will detect what character is the user trying to draw. First it will detect the gesture with the movement of a bottle cap held in the hand and then with that captured gesture it will generate an image using openCV and with the help of the image generated it will recognize the character. The gesture detection part will be performed using openCV while character recognition part will be completely based on CNN(Convolutional Neural Networks).



My aim is to first detect a pattern created by user with his gesture in front of the camera . For this purpose we have used the computer vision library OPENCV . Using OPENCV we are generating an image from the pattern detected by the gesture of the user. Our next step is to recognize this image as a character . For this purpose we have trained a CNN deep learning model which recognizes the image given as an test input as the most closely resembling character . We have used the MNIST data set for the model training.



As mentioned earlier , after training our model we need a testing image for the prediction for which we have used OpenCv . OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV is a cross-platform library using which we can develop real-time computer vision applications. It mainly focuses on image processing, video capture and analysis including features like face detection and object detection








![](/character_recognition/sample3.png)








![](/character_recognition/sample2.png)



