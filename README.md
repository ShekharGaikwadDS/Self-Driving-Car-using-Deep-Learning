# ML Object Detection Model

This repository contains a prototype machine learning model for identifying and detecting various objects such as traffic lights, stop signs, vehicles (cars, bicycles, trucks), pedestrians, and animals.

The primary goal of our object detection algorithm is to be fast enough to run inference in real-time on commodity hardware (CPU only) while ensuring high accuracy to prioritize safety.

## Demo

Here is a snapshot of the object detection results achieved using our model:

![Object Detection Demo](https://drive.google.com/uc?id=1Ty9Bjh4HiCgSbXbNQ8gTGA_z4ggxZbf8)

## Why YOLO V5?

We have chosen to utilize pre-trained YOLO V5 models for our specific use case. These models have been trained using the COCO Dataset, which contains the target classes we want to detect, including:

- Car
- Motorbike
- Aeroplane
- Bus
- Truck
- Traffic light
- Person
- and more...

Here are some key reasons for selecting YOLO V5:

- YOLO V5 is built on the popular PyTorch framework, which is widely used in the applied computer vision community.
- PyTorch models can be easily migrated to other frameworks such as ONNX and TensorFlow.
- YOLO V5 is faster than YOLO V4 and offers five checkpoints catering to different memory and speed requirements.

For more detailed information about YOLO V5, you can refer to this informative blog post: [YOLOv5 is Here!](https://blog.roboflow.com/yolov5-is-here/)

We will be utilizing the ONNX format of YOLO V5 for our implementation.

## What is ONNX?

ONNX (Open Neural Network Exchange) is an open format designed to represent machine learning models. It defines a common set of operators, which are the building blocks of machine learning and deep learning models, as well as a standard file format. This enables AI developers to use models with various frameworks, tools, runtimes, and compilers.

The use of ONNX allows solutions developed using one framework to be easily deployed in another framework and vice versa. For more information about ONNX, please visit their official website: [https://onnx.ai/](https://onnx.ai/)

<big><big><big><big>

### Test

</big></big></big></big>

Feel free to explore this repository and leverage our ML object detection model for your own projects. If you have any questions or suggestions, please don't hesitate to reach out.

Happy detecting!
