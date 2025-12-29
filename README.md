# Multi-Object Tracking with YOLOv11 & DeepSORT

This repository provides a Python implementation of a high-performance object tracking pipeline using the **Ikomia API**. It combines the detection power of **YOLOv11** with the robust identity-assignment of the **DeepSORT** algorithm.



## 📌 Features
* **YOLOv11 Integration**: High-accuracy object detection.
* **DeepSORT Tracking**: Maintains consistent object IDs across frames, even through partial occlusions.
* **GPU Acceleration**: Native CUDA support for real-time inference.
* **Auto-rendering**: Generates a processed video file (`.mp4`) with bounding boxes and tracking IDs.

## 🛠️ Installation

1. **Install Ikomia and OpenCV**:

   ```  
   pip install ikomia opencv-python

   ```
## Clone this repository:

```  
git clone [https://github.com/your-username/yolo-deepsort-tracking.git](https://github.com/your-username/yolo-deepsort-tracking.git)
cd yolo-deepsort-trackingn

```

## Quick Start
Place your input video in the project directory (e.g., walking.mp4).

Run the script:

```
python main.py

```


Press 'q' during playback to stop processing and save the output.
