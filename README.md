# Object Detection using YOLOv3

This repository contains code for real-time object detection using YOLOv3 (You Only Look Once) model. The YOLO model is trained on the COCO (Common Objects in Context) dataset for detecting various objects in images.

## Overview

This Python script utilizes OpenCV and NumPy libraries to perform object detection on a live camera feed or video input. The YOLOv3 model is loaded from pre-trained weights and configuration files. Detected objects are labeled and bounded with rectangles in the output frame.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/lokesh-jonna/object_detection.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd object_detection
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure your camera is connected or specify the video file path in the script.

2. Run the Python script:

   ```bash
   python obj.py
   ```

3. Press 'q' key to exit the application.

## Customization

You can customize the confidence threshold and Non-Maximum Suppression (NMS) threshold in the script according to your requirements. Additionally, you can modify the YOLO configuration and weights files to use different versions or trained models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use this template in your repository. You can copy and paste it directly into your README.md file on GitHub.
