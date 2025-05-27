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
