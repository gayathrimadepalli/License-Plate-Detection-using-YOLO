# License-Plate-Detection-using-YOLO
# License Plate Detection using YOLO

This repository contains code and resources for automatic license plate detection using YOLOv3 (You Only Look Once) object detection algorithm.

## Overview

This project implements a license plate detection system using a pre-trained YOLOv3 model. The system can identify and highlight license plates in images with bounding boxes and proper labeling.

## Features

- Real-time license plate detection
- High accuracy detection using YOLOv3 architecture
- Support for various image formats
- Clear visual output with bounding boxes

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib (for visualization)
- Google Colab (optional, for cloud-based execution)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/misbah4064/yolo-license-plate-detection.git
   cd yolo-license-plate-detection
   ```

2. Download the pre-trained weights:
   ```
   # Using gdown if you're on Google Colab
   !gdown https://drive.google.com/uc?id=1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc
   ```

## Usage

1. Import the necessary libraries (OpenCV, NumPy, Matplotlib)
2. Load your input image
3. Use the `objectDetector()` function to detect license plates
4. Visualize or save the results

## How It Works

The system uses YOLOv3 architecture trained specifically for license plate detection:

1. The input image is preprocessed and fed into the YOLO neural network
2. The network predicts bounding boxes and confidence scores
3. Non-maximum suppression is applied to filter out overlapping detections
4. The final detections are drawn on the image with appropriate labels

## Model Details

- Architecture: YOLOv3 (Darknet)
- Input size: 416x416
- Confidence threshold: 0.5
- NMS threshold: 0.4
- Trained to detect license plates across various conditions

## Results

The system can successfully detect license plates in different lighting conditions, angles, and distances. Sample results can be viewed by running the provided example code.

## Future Improvements

- Add license plate recognition (OCR) to read the detected plates
- Implement video processing capabilities
- Train on more diverse datasets for improved accuracy
- Optimize for mobile deployment

## Acknowledgements

- Original YOLOv3 implementation by Joseph Redmon
- Dataset contributors
- Special thanks to the computer vision community

## License

[Include your license information here]

## Contact

[Your contact information]
