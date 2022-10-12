# Gesture-Recognition-Deep-Learning 
Project to recognize hand gesture using neural networks.

## Team
 Abhineet Chauhan & Arvind Agnihotri.
 
## Problem Statement 
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

- Thumbs up:  Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backwards 10 seconds
- Right swipe: 'Jump' forward 10 seconds  
- Stop: Pause the movie

Each video is a sequence of 30 frames (or images)

## Understanding the Dataset
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 

The data is in a folder (https://drive.google.com/drive/folders/18q3ImiHjhjzk2UN1PzkW3q1wSbnIaNIH?usp=sharing). The file contains a 'train' and a 'val' folder with two CSV files for the two folders.

## Model Overview

| Model Name: Project Data | Model Type | Number of parameters | Augment Data | Model Size (in MB) | Highest Validation accuracy | Corres-ponding Training accuracy | Observations                                                                                                                                                               |

### Contributers:
 - [Abhineet Chauhan](https://github.com/ABHI8896)
 - [Arvind Agnihotri]( https://github.com/Arvind-Agnihotri)
