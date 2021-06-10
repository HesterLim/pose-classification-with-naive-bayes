# pose-classification-with-naive-bayes

## Overview
Human pose recognition, and related tasks like gesture recognition and action recognition, are important tasks for AI systems that interact with people. There are many algorithms for classifying pose; for example, deep convolutional neural networks can be trained to classify pose directly from images. However, these methods tend to be “black boxes” and it’s difficult to understand what features they are using. Another approach, which we will use in this Project, uses neural networks to first identify keypoints corresponding to the main parts of the body (as shown above), and then learns to recognize pose based on the positions of these body parts.
In this project, you will implement a supervised na ̈ıve Bayes learner to classify pose from key- points provided by a deep convolutional neural network. You will train, test, and evaluate your classifier on a provided dataset, and then you will have a choice of either extending this basic model in various ways, or using it to answer some conceptual questions about na ̈ıve Bayes.

## Pre-requisite and libraries used:
1. pandas
2. numpy
3. matplotlib.pyplot
4. math
5. Python 3
6. scipy
7. sklearn

## Setup 
1. Navigate to the read_data() function to set up the link for both test_csv and train_csv to your local directory.
2. Once done, navigate to kernel and press restart and run all. The notebook should provide all the expected output. 

## Contributors
- Hester 
- Kennedy 

## Coding Mark 
- 8/8 (100%)
