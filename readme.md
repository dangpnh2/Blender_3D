# CS579-Final Project

## Introduction
This is the implementation of "3D Bounding Box Estimation Using Deep Learning and Geometry" on Blender

## Dependency
* [Numpy](http://www.numpy.org/)
* [Blender (2.79)](https://www.blender.org/)

## Usage
This project comprises 2 main module
+ ## 2D object detection:
    YOLO: Please follow the instruction from this link: https://timebutt.github.io/static/how-to-train-yolov2-to-detect-custom-objects/ or use the pretrained model in yolo_coca_minimal_files.
    
    SSD: https://www.dlology.com/blog/how-to-train-an-object-detection-model-easy-for-free/ or use the pretrained model in ssd_coca folder.

+ ## 2D-3D conversion:
    Please check the function calculate_loc in Blender for more detail.
    
+ ## Blender environment (*.blend files)
    Open Blender and load project (file *.blend).
    Include the 2D object detection and 3D MultiBinCNN files into Blender envi from line 425->429
    
    Replace coordinate of 2D detection at line 530 and orientation angle at line 532.



