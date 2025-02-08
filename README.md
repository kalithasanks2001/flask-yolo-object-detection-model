# flask-yolo-object-detection-model

YOLO stands for **"You Only Look Once."** It is a real-time object detection algorithm known for its speed and accuracy. 

YOLO processes an entire image in a single forward pass of a neural network, making it significantly faster compared to traditional region-based detection methods.

- Developed a Flask-based real-time object detection system integrating the YOLO model to process live video streams dynamically.  
- Designed an API to accept video sources and region coordinates for flexible detection settings.  
- Implemented region-based detection: the left side exclusively detects persons, while the right side identifies cars and two-wheelers.  
- Optimized video processing using OpenCV and parallelized inference, improving detection speed and accuracy.
