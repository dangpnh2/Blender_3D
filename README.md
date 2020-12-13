# CS579-Final Project

## Introduction
This is the implementation of "3D Bounding Box Estimation Using Deep Learning and Geometry" on Blender

## Dependency
* [Darknet (for training YOLO)](https://github.com/pjreddie/darknet) 
* [Tensorflow (for training SSD)](https://www.dlology.com/blog/how-to-train-an-object-detection-model-easy-for-free/) 
* [Pytorch (for training orientation angle)](https://pytorch.org/)
* [Numpy](http://www.numpy.org/)
* [Blender (2.79)](https://www.blender.org/)


## Components:
This project comprises 3 main components:
+ ## 2D object detection:
    YOLO: Please follow the instruction from this link: https://timebutt.github.io/static/how-to-train-yolov2-to-detect-custom-objects/ or use the pretrained model in yolo_coca_minimal_files.
    
    SSD:  or use the pretrained model in ssd_coca folder.

+ ## 3D properties regression:
    Use pytorch_3DBB_orientation.ipynb for training the orientation angle.
    
+ ## 2D-3D conversion:
    Please check the function calculate_loc in Blender for more detail.
    
## Run detection in Blender:
    Open Blender and load project (file *.blend).
    Include the 2D object detection and 3D MultiBinCNN environment into Blender envi from line 425->429
    
    Replace coordinate of 2D detection at line 530 and orientation angle at line 532.
