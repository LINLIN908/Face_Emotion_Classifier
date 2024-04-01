# Face classification and detection.
Real-time face detection and emotion/gender classification using fer2013/IMDB datasets with a keras CNN model and openCV.
* IMDB gender classification test accuracy: 96%.
* fer2013 emotion classification test accuracy: 66%.

For more information please consult the [publication](https://github.com/oarriaga/face_classification/blob/master/report.pdf)
------------------------------------------------
## Introduction
This project provides a code example for real-time recognition of user emotions and logging the data into a CSV file. The code is implemented based on fer2013/IMDB datasets with a keras CNN model and openCV to achieve emotion recognition functionality and provides a simple example demonstrating how to use it.

## Background
While utilizing the face_classification project by Octavio Arriaga and his team on GitHub (https://github.com/oarriaga/face_classification), we found the program to be highly practical and efficient. However, we encountered some issues:

*Inability to output and log real-time emotion recognition data locally.
*Lack of pre-packaged executable files for easier deployment.

## Key Features

* Real-time Emotion Recognition: Recognize the user's emotion in real-time.
* Data Logging: Log the emotion recognition results into a CSV file for further analysis or visualization.

# Emotion examples:

![alt tag](images/emotion_classification.jpg)

Real-time demo:
<div align='center'>
  <img src='images/color_demo.gif' width='400px'>
</div>

CSV file:
![alt tag](images/CSV_file.jpg)

Emotion data:
![alt tag](images/Emotion.jpg)


## Instructions

### Run real-time emotion demo and:
> python3 video_emotion_color_demo.py
![alt tag](images/Example_exe.jpg)
