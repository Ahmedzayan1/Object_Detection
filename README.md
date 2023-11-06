# Object_Detection
Object Detection using YOLO pre-trained model

# Real-Time Object Detection with YOLO and OpenCV

This Python program uses the YOLO (You Only Look Once) object detection model and OpenCV to perform real-time object detection through a webcam feed. It identifies and draws bounding boxes around various objects in the webcam stream.

## Prerequisites
Before running the program, make sure to install the required dependencies:

```bash
pip install opencv-python-headless
pip install ultralytics
```
## Usage
1.Ensure your webcam is connected and accessible.

2.Run the Python script:

```bash
python your_script_name.py
```
3.The program will start the webcam and display real-time object detection.

4.Press 'x' to exit the program.

### Model and Class Names
The program uses the YOLO model with pre-trained weights (yolo-Weights/yolov8n.pt). The model can detect various objects, and the following class names are used:

person
bicycle
car
motorbike
aeroplane
bus
train
truck
boat
traffic light
...
For a complete list of class names, refer to the classNames list in the script.

## Understanding the Output
Bounding boxes are drawn around detected objects.
Confidence levels for each detection are displayed.
The corresponding class name for each detected object is printed.

## Dependencies
OpenCV - Open Source Computer Vision Library
Ultralytics YOLO - YOLOv5 implementation by Ultralytics
Contributing
If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License, allowing you to use, modify, and distribute the code freely.

Thank you for using Real-Time Object Detection with YOLO and OpenCV! If you have any questions or suggestions, feel free to open an issue or reach out to the project contributors.

Happy detecting! 📷🚗
