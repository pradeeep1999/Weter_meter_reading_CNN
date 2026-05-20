# Water Meter Reading System using Quantized CNN

## Overview

The Water Meter Reading System uses a Quantized Convolutional Neural Network (CNN) to automatically detect and read water meter values from images. The model is optimized for edge devices, enabling fast and efficient inference with low memory and computational requirements.

## Features

### 📷 Automatic Meter Reading

* Extracts numerical readings from water meter images
* Supports digit detection and recognition
* Works under varying lighting conditions

### 🧠 Quantized CNN Model

* Uses quantized neural network for reduced model size
* Optimized for embedded and edge deployment
* Faster inference with minimal accuracy loss

### ⚡ Edge Deployment

* Suitable for microcontrollers and low-power devices
* Can run on Raspberry Pi or similar edge hardware
* Offline processing capability

## System Architecture

* Image acquisition module (camera / ESP32-CAM / mobile camera)
* Preprocessing pipeline (grayscale, thresholding, ROI extraction)
* Quantized CNN model for digit recognition
* Post-processing to form final meter reading output

## Workflow

1. Capture water meter image
2. Preprocess image (resize, normalize, ROI extraction)
3. Run quantized CNN inference
4. Detect digits and sequence them
5. Output final water consumption reading

## Applications

* Smart water metering systems
* Utility billing automation
* Remote infrastructure monitoring
* Smart city IoT systems
* Industrial fluid monitoring

## Technologies Used

* Python
* TensorFlow / TensorFlow Lite
* Convolutional Neural Networks (CNN)
* Model Quantization (INT8 / Float16)
* OpenCV for image processing
* Edge AI deployment tools

## Advantages

* Low power consumption
* Fast real-time inference
* Reduced model size for embedded systems
* Eliminates manual meter reading
* Scalable for large deployments

## Future Improvements

* Integration with cloud billing system
* Real-time IoT data upload via MQTT
* Improved digit segmentation accuracy
* Multi-meter detection in a single frame
* Mobile app integration

## Author

Embedded AI & IoT Engineer
