# Pen Detection using YOLOv8 and Webcam
This project implements real-time pen detection using the YOLOv8 object detection model. The model was trained on custom-annotated data (using Roboflow) to accurately identify pens from webcam video input.
## Features 
- Real-time object detection using YOLOv8
- Custom-trained model for pen detection
- Webcam input and live bounding box display
- Easy integration with other gesture or control-based projects
## How It Works
- Annotate images of pens using Roboflow and export in YOLO format
- Train a YOLOv8 model in Python
- Capture video frames from webcam
- Use the YOLO model to detect pens in each frame
- Bounding boxes and labels for detected pens
## Download Model & Dataset
Download the trained YOLOv8 model here: https://drive.google.com/file/d/1X11tzurnSmXAa3S5EZ4z0oLagfzVQ74y/view?usp=drive_link
Download the custom dataset from Roboflow: 
!pip install roboflow

from roboflow import Roboflow
rf = Roboflow(api_key="lC2FRdEFWLGU0wIfa7Xn")
project = rf.workspace("arhprojects").project("pen-detector-lqz9h")
version = project.version(2)
dataset = version.download("yolov8")
                
