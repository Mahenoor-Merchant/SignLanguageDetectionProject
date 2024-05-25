# End-to-end-Sign-Language-Detection

## Overview
This repository contains the implementation of sign language detection using YOLOv5. It includes a Python application (`app.py`) that allows users to upload images or use a live camera feed for sign language detection.

## Usage
1. Clone the repository
   
2. Create a Python 3.7 virtual environment:
   ```
   conda create -n env python=3.7
   ```
3. Activate the virtual environment:
   ```
   conda activate env
   ```
4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Run the application:
   ```
   python app.py
   ```

## Usage Details
- Upon running the `app.py` script, the user interface will be launched.
- Users can upload images containing sign language gestures or choose to use a live camera feed for real-time detection  by adding '/live' to the url path.
- The application will display the detected sign language gestures.


## Acknowledgements
- YOLOv5 GitHub repository: [link](https://github.com/ultralytics/yolov5)

## References

- [YOLOv5 GitHub Repository](https://github.com/ultralytics/yolov5)

## Contributions
Contributions to this project are welcomed.
