Video Synopsis
Environment
Ubuntu 16.04

CMake version 3.10.2

OpenCV 3.4.0

dlib 19.9

CUDA 8.0 and cuDNN 6

Protobuf 3.5.1

Introduction
This project is inspired by multiple open-source projects (exact names unknown). It utilizes SSD (Single Shot MultiBox Detector) for object detection and tracking in videos, employing Particle Filtering or Kalman Filtering for tracking. Poisson image editing is used to overlay each tracked object onto the background.

Notes:
SSD model files can be downloaded from: SSD Caffe Repository.

Due to differences in CUDA and other software versions, it is recommended to compile the library files from the SSD Caffe repository and replace the necessary Caffe header files accordingly.
