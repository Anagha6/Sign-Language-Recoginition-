# **Sign Language Recoginition System**

## **CONTENTS**
  1 . Introduction

2.  Problem Statement

3.  Data Description

4.  Toolkit

5. Installation

6. Training and Evaluation

7. Further modification

  8 . UI Development


## **INTRODUCTION**
Inability to speak is considered to be true disability. People with this disability
use different modes to communicate with others, there are number of methods
available for their communication one such common method of
communication  is  sign  language.
Developing sign language application for deaf people can be very important,
as they’ll be able to communicate easily with even those who don’t understand
sign language.

Dumb people use hand signs to communicate, hence normal people face problem in recognizing their language by signs made. Hence there is a need of the systems which recognizes the different signs and conveys the information to the normal people.
In this presentation, we will be demonstrating a Computer Vision demo using YOLOv5 on the American Sign Language Dataset including 26 classes.

## **PROBLEM STATEMENT**
Our project aims at taking the basic step in bridging the
communication gap between normal people, deaf and dumb people using sign
language through image processing and computer vision.

## **DATA DESCRIPTION**
For this, We have used American Sign Language dataset that was collected from the gituhub. The dataset consists of 3399 images having 26 American Sign language alphabets. This dataset was used because of the availability of annotations which were required for training our model.The images for the training and testing sets are in train  and test files respectively, and additional information about each image is in labels.

Link for the dataset:

       American Sign Language : https://universe.roboflow.com/sign-language/american-language/dataset/1
       
## **TOOLKIT**
**Yolo model:** You Only Look Once (YOLO) family of detection frameworks aim to build a real time object detector, which what they lack in small differences of accuracy when compared to the two stage detectors, are able to provide faster inferences.It predicts over limited bounding boxes generated by splitting image into a grid of cells, with each cell being responsible for classification and generation of bounding boxes, which are then consolidated by NMS.

YOLOv5 architecture:

![image](https://user-images.githubusercontent.com/98939596/202833163-8352fe2c-13c2-4be1-8067-4a9a27faad15.png)

The model identifies signs in real time as well as with input image or audio and builds bounding boxes showing label with confidence value.The model is showcased using streamlit which can take input as an image.

**Why YOLOV5**

YOLOv5 has been designed to be super easy to get started and simple to learn. We prioritize real-world results.

## **INSTALLATION**

Clone repo and install requirements.txt in a Python>=3.7.0 environment, including PyTorch>=1.7.

To run this code in your local system you have to download this repository using :

git clone https://github.com/Anagha6/Sign-Language-Recoginition-.git  # clone
cd yolov5

install the required python packages using:

pip install -r requirements.txt  # install

## **TRAINING AND EVALUATION**

## **FURTHER MODIFICATIONS**

We can also try another model like CNN for real time sign language detection.


## **UI DEVELOPMENT**

Run

Clone the repo in virtual environment and open the website using the following command:

streamlit run app.py

![Screenshot (43)](https://user-images.githubusercontent.com/98939596/202833714-f56397cf-0909-48e7-8ad2-5d881534506f.png)

## **AUTHOR**

Name : Anagha Ashok





             
     




