
# Person Tracking using YOLO

## Description

This project implements real-time person tracking using the YOLO (You Only Look Once) object detection model with OpenCV and Python. It detects and tracks people in video streams and displays their movement trajectories.

## Features

- Real-time person detection using YOLOv3.
- Tracking of detected persons with trajectory plotting.
- Counting the number of people detected.
- Adjustable detection thresholds for accuracy.

## Requirements

Ensure you have the following dependencies installed before running the script:

```bash
pip install opencv-python numpy
```

## Files in this Repository

- `main.py` - Main script for person detection and tracking.
- `yolov3.cfg` - YOLOv3 configuration file.
- `coco.names` - COCO dataset class names file.

## How to Run

1. Download the YOLOv3 weights file from [this link](https://pjreddie.com/media/files/yolov3.weights) and place it in the same directory.
2. Run the script using the following command:

```bash
python main.py
```

## Usage

- The script will open a window displaying detected persons in real-time.
- Press `q` to exit the program.

## Acknowledgments

YOLO (You Only Look Once)** - For real-time object detection.
OpenCV - For image processing and visualization.



