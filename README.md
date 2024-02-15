# Deep Image Recognition 

## Description

In this project I tried to implement a Siamese neural networks for one-shot image recognition from scratch .I implemented this code using a paper which I put here.

You can use this project for deep facial recognition and recognize a face which model has trained on from others. This is great project to understand both siamese neural networks and learning to how to code your won model.


## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)

## Installation

To run this project you will need :
  -Tensorflow and Keras
  -CV2
  -Matplotlib
  -numpy

Labeled faces in the wild Dataset : https://vis-www.cs.umass.edu/lfw/
Also you will need a webcam 

## Usage

First download the dataset then create a folder named 'data' and also create 3 subfolders of 'anchor' , 'negative' and 'positive' in data folder.
Dataset will only be the negative data so you will need to create positive and anchor data your self.
When you run the code you will take pictures of the target with CV2 for positive and anchor data.(500 data for each will do fine)

Then create a folder named 'application_data' which has two subfolders of 'input_image' and 'validation_images' then copy a few of poistive data to 'validation_images'.
after this you can easily train the model and try new input images with your webcam.


