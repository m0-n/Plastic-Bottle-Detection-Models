# Plastic-Bottle-Detection

A object detection model for plastic bottles in water in TensorFlow (.pb) and TensorFlow Lite (.tflite) format. 

Dataset used for training: https://github.com/m0-n/Plastic-Bottles-Dataset


<img src="https://i.imgur.com/fhZ6CaE.jpg">

<img src="https://i.imgur.com/x1Sfuny.jpg">

Results may vary.

The model is suited for edge devices, such as the Raspberry Pi. When device performance permits, split camera input in 3x3 tiles and run inference on all simultaneously. 
