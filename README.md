# TensorFlow Lite Object Detection Android Demo

### Overview

DishCoin is an app, powered by Computer Vision, that is made to assess your dishwashing efficiency.
Load your DishCoin wallet with BitCoin and compete with your friends for the goal of saving
water through dishwashing efficiency sagas. The winner takes it all! (screenshot1.png)

### The Tech
The neural network used for the detection of people, cuttlery and dishes is the:

[MobileNet SSD](https://tfhub.dev/tensorflow/lite-model/ssd_mobilenet_v1/1/metadata/2),
model trained on the [COCO dataset](http://cocodataset.org/). 
This application should be run on a physical Android device.