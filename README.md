# Plastic-Bottle-Detection

A object detection model for plastic bottles in water in TensorFlow (.pb) and TensorFlow Lite (.tflite) format. 

Dataset used for training: https://github.com/m0-n/Plastic-Bottles-Dataset

Recall: ~59.1% 
Precision: ~56.5%
at confidence threshold of 0.22

Results may vary.

The model is suited for edge devices, such as the Raspberry Pi. When device performance permits, split camera input in 3x3 tiles and run inference on all simultaneously. 
