# People Counting System

This script processes a video file to count people entering and exiting specific regions of interest.

## Summary

The `people_counter.py` script utilizes YOLO object detection to detect people in each frame of the video. It then tracks their movements using a custom object tracking module. The script determines whether individuals are entering or exiting designated areas of interest defined as polygons on the video frame.

## Requirements

- Python 3.x
- OpenCV
- pandas
- numpy
- ultralytics (for YOLO object detection)
- torch
- Tracker module (custom module for object tracking)

## Usage

1. Make sure the video file `peoplecount1.mp4` is in the specified path.
2. Install the required dependencies using pip:

## File Structure

- `coco.txt`: File containing class labels for the COCO dataset.
- `yolov8s.pt`: YOLOv8s model weights.
- `tracker.py`: Custom module for object tracking.

This structure provides a clear overview of the files and directories in your project, making it easier for users to navigate and understand the project's components.
