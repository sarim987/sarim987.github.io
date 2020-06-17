# sarim987.github.io

# People Tracking in Varying Environment Conditions 
By Sarim Ahmed
Introduction

- Model Training Layer
- Darknet computer vision backend
- Quick training and classification of images

The video analytics industry has grown rapidly in the last couple years. With advancements in computer vision, companies are looking to automate many manual processes as well as making video cameras smarter in detecting anomalies such as crowd movement. Unfortunately much of the camera infrastructure currently installed is outdated and the quality tends to greatly vary. Conditions such as sudden light changes, snow and rain storms, fog, night to day shifts, all can make accurately analyzing video difficult. However, many researchers have looked into the topic to develop new ways to combat these issues. The goal of these researchers and this field of study is to create a real time analytics system that can accurately count the people and crowds using the currently installed video surveillance systems. The system will need to be efficient enough to run on low end devices as companies may need to install several of them. They will also want to keep running costs as low as possible. We explored several methods of people counting that use off-the-shelf libraries and open source software. The methods described are also capable of running on low end devices while maintaining accuracy.

# Analysis Layer
background subtraction algorithm to develop a heuristic model

# Tracking Algorithm
Tracking the movement of each detection blob
Algorithms match each tracked object with the current detection.

# Running Software
Only need URL of the IP camera stream as an input
Values can also visualized with online graphs and time based charts. 

# Conclusion
Able to create a stack where each image or a set of images are sent through each layer and returns a set of detections
Counts can also be used for security to make sure people are not doing things they are not supposed to be doing
