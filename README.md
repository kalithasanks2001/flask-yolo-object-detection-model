# flask-yolo-object-detection-model

YOLO stands for **"You Only Look Once."** It is a real-time object detection algorithm known for its speed and accuracy. 

YOLO processes an entire image in a single forward pass of a neural network, making it significantly faster compared to traditional region-based detection methods.

- Developed a Flask-based real-time object detection system integrating the YOLO model to process live video streams dynamically.  
- Designed an API to accept video sources and region coordinates for flexible detection settings.  
- Implemented region-based detection: the left side exclusively detects persons, while the right side identifies cars and two-wheelers.  
- Optimized video processing using OpenCV and parallelized inference, improving detection speed and accuracy.

**Overview**
This project is a Flask-based real-time object detection system integrating the YOLO model to process video streams dynamically. The system classifies objects based on predefined regions of interest (ROIs):

The left side of the video detects persons.
The right side of the video detects cars and two-wheelers.

**Features**
✅ Dynamic Video Input – Accepts video sources via an API request.
✅ Region-Based Detection – Differentiates objects based on predefined regions.
✅ Real-Time Processing – Uses YOLO for fast object detection.
✅ Flask API Integration – Enables dynamic configuration of video sources and detection regions.
✅ Optimized Performance – Utilizes OpenCV for efficient frame processing.

**Project Workflow**
The Flask API receives the video source and detection region coordinates.
The YOLO model processes each frame and detects objects.
Objects in the left half are checked for persons, while objects in the right half are checked for cars and two-wheelers.
The processed video with bounding boxes is displayed or saved.
