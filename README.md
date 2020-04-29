# Yolov4-Object-Detection
Yolov4 Object Detection

## Introduction

Yolov4 implementation inspired by:-

YOLOv4 (Tensorflow backend) inspired by [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet).

## Quick Start

1. Download YOLOv4 weights from [yolov4.weights](https://drive.google.com/open?id=1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT).
2. Also download automatically weights when run yolo.py and pass argument --download-model check below for command.
--> python yolo.py --download-model
3. Change arguments according to filepaths.
4. Run yolo.py.
--> python yolo.py -i <path of image>
--> python yolo.py -v <path of video used for inference> -vo <path of output folder where you want to save the inference result of video>
--> python yolo.py -no_argument then it automatically use your webcam for inference.


## TODO

How to train yolov4 model for your own custom dataset.

## Thanks!
