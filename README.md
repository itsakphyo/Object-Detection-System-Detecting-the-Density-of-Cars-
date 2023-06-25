# Object-Detection-System-Detecting-the-Density-of-Cars-
This repository contains a Python code that demonstrates object detection using the YOLOv4 algorithm. The code utilizes OpenCV's deep neural network module (dnn) to perform real-time object detection on images or video frames.
## Prerequisites
    Python 3.x
    OpenCV (cv2)
    NumPy

## Getting Started
    Clone this repository to your local machine or download the source code directly.
    Download the YOLOv4 weights from the following link: YOLOv4 Weights.[link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi_uOjb-d3_AhVPbmwGHR40BnIQFnoECBYQAQ&url=https%3A%2F%2Fgithub.com%2FAlexeyAB%2Fdarknet%2Freleases%2Fdownload%2Fdarknet_yolo_v3_optimal%2Fyolov4.weights&usg=AOvVaw30if4joxtTaS8DAh12vYQ4&opi=89978449)
    Place the downloaded weights file in the same directory as the code file



## Usage
    Instantiate the ObjectDetection class, optionally providing the paths to the YOLOv4 weights file (weights_path) and the configuration file (cfg_path).
    Load the class names by calling the load_class_names method, which reads the class names from the classes.txt file.
    Capture an image or video frame using OpenCV's VideoCapture class. You can specify the path to the image or video file in the VideoCapture constructor.
    Call the detect method of the ObjectDetection instance, passing in the captured frame. This method returns the detected objects' class IDs, scores, and bounding boxes.
    Iterate over the detected objects and draw rectangles around them on the frame.
    Display the annotated frame using OpenCV's imshow function.
    Wait for a specified duration (in milliseconds) using waitKey, and then close the window.

## Installation
To install the required dependencies, run the following command:
```python
pip install opencv-python numpy
