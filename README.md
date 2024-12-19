# YOLO Gesture Detection

recognition systems play a vital role in bridging communication gaps for the hearing and speech-impaired community. This project focuses on recognizing PSL gestures using a state-of-the-art YOLOv8-CSP model, optimized for real-time performance and high accuracy.
Said model is trained and tested on a custom dataset.
In addition, opencv is used in tandem with the model to perform live detection as well.


## Contents
~~~
/data:                         Dataset used during the project.
/images:                       Images and examples used in the Jupyter Notebook and readme.
/yolov8:                       The YOLOv8 model and all its utilities.
README.md:                     You're reading it.
yolo_gesture_detection.ipynb:  Code for the creation, training, testing, and evaluation of a YOLOv8 model.
yolov8csp.pt:                  A modified YOLOv8 model.
~~~
## Features

- Real-time hand gesture detection and classification.
- Support for live video streams via webcam or external camera.
- Configurable detection confidence thresholds.
- Model training pipeline for custom PSL datasets.

---

## Requirements

### Hardware Requirements
- GPU-enabled system with CUDA support (NVIDIA GPU recommended).
- At least 8GB RAM.

### Software Requirements
- Python 3.8 or later.
- Libraries:
  - `ultralytics`
  - `opencv-python`
  - `numpy`
  - `torch` (with GPU support)
  - `matplotlib` (for visualizing results)

Install dependencies via:
```bash
pip install ultralytics opencv-python numpy torch matplotlib
```
### link to download dataset 
https://drive.google.com/drive/folders/19tqmHaVYL_JTXJB8nUSdrmlxJ1ON1FoY?usp=sharing
