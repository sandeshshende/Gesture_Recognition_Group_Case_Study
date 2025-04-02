# 3D CNN for Smart TV Control via Hand Gesture Recognition

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
This project focuses on developing a **3D Convolutional Neural Network (3D CNN)** for real-time hand gesture recognition, enabling users to control a smart TV without a remote. The model uses a webcam mounted on the TV to recognize predefined gestures and execute corresponding commands.

### Background
- **Objective**: Create an intuitive, remote-free TV control system using hand gestures.
- **Gestures**: 
  - Thumbs Up → Increase volume
  - Thumbs Down → Decrease volume
  - Left Swipe → Rewind video by 10 seconds
  - Right Swipe → Fast-forward video by 10 seconds
  - Stop Gesture → Pause playback
- **Dataset**: Hundreds of labeled video clips with varying resolutions (360×360 and 120×160 pixels).

## Technologies Used
- **TensorFlow/Keras** - Version 2.10.0
- **OpenCV** - Version 4.5.5
- **NumPy** - Version 1.21.5
- **Pandas** - Version 1.3.5
- **Matplotlib** - Version 3.5.1

## Conclusions
- **Model Performance**: The final model achieved **95% validation accuracy**, demonstrating excellent performance in recognizing hand gestures.
- **Efficiency**: The model balances accuracy and computational efficiency, making it suitable for real-time deployment on embedded systems.
- **Transfer Learning**: Using MobileNet with transfer learning significantly improved model performance compared to training from scratch.
- **GRU Integration**: Incorporating GRUs reduced training time and complexity while maintaining high accuracy.

## Acknowledgements
- This project was inspired by the need for intuitive human-computer interaction in smart TV systems.
- References:
  - [Keras Documentation: Image Data Loading](https://keras.io/preprocessing/image/)
  - [ImageNet Database](http://www.image-net.org/)
  - [MobileNet Model](https://github.com/fchollet/deep-learning-models/releases/download/v0.6/mobilenet_1_0_224_tf_no_top.h5)
  - [ImageNet Class Labels](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a)

## Contact
Created by [@Sandesh_Shende & @SaadTeli] - feel free to contact me for further inquiries or collaboration opportunities!
