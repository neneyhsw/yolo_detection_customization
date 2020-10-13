# yolo_detection_customization
This file refer to darknet project. The source is from the src directory in darknet.  
This repository will modify some source code to implement customized function.  
These files are from darknet repository.  

## Source Code
The image.c file shows the detection box for detecting picture. (cmd: ./darknet detector test)  
The image_opencv.cpp file shows the detection box for detecting video. (cmd: ./darknet detector demo)  
Therefore, we can modify these files for customizing our needs.  

In this repository, I will modify the image.c to find the center point of detection box.  
Modifying image_opencv.cpp to set a box at center, and calculate the IoU between center box and detection box.  
The application can compare the distance by the IoU.  
If IoU is bigger, the distance is less.  

Example:  

<img src=https://github.com/neneyhsw/yolo_detection_customization/blob/main/alert.png width="400" height="300">

## Reference
https://github.com/AlexeyAB/darknet
