---
date: "2020-07-10"
# external_link: https://github.com/hashmis79/Moodylyser
tags:
- Machine Learning
- OpenCV
- CNN
title: Moodylyser
url_code: https://github.com/hashmis79/Moodylyser
---

**Moodylyser – Real-time Emotion Detection using Computer Vision**
Project Overview: Moodylyser is a real-time emotion detection system that uses computer vision and machine learning to identify and analyze human emotions through facial gestures. The project leverages a Convolutional Neural Network (CNN) to extract facial features and detect emotions from a live video feed. The emotions detected include "Anger," "Disgust," "Fear," "Happiness," "Sadness," "Surprise," and "Neutral."

**Development Process:**
Face Detection and Preprocessing:
Using OpenCV, the system captures a live video feed and detects the user's face, activating the emotion recognition algorithm. The video is converted to grayscale and fed into the CNN model after resizing to the required dimensions.

**Model Architecture:**
The CNN model was implemented using Keras, with over 1.3 million trainable parameters. The model was trained on the FER2013 dataset to classify facial gestures into corresponding emotions. Techniques such as dropouts, regularization, and kernel constraints were used to enhance the model's performance.

**Facial Landmarks Detection:**
The system also incorporates the dlib library to detect 64 facial landmarks, which are then fed into the CNN to improve emotion detection accuracy.
<!--more-->
