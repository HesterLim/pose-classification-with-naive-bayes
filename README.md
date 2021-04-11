# pose-classification-with-naive-bayes
Student ID(s): 1039169, 1044793

## Overview
Human pose recognition, and related tasks like gesture recognition and action recognition, are important tasks for AI systems that interact with people. There are many algorithms for classifying pose; for example, deep convolutional neural networks can be trained to classify pose directly from images. However, these methods tend to be “black boxes” and it’s difficult to understand what features they are using. Another approach, which we will use in this Project, uses neural networks to first identify keypoints corresponding to the main parts of the body (as shown above), and then learns to recognize pose based on the positions of these body parts.
In this project, you will implement a supervised na ̈ıve Bayes learner to classify pose from key- points provided by a deep convolutional neural network. You will train, test, and evaluate your classifier on a provided dataset, and then you will have a choice of either extending this basic model in various ways, or using it to answer some conceptual questions about na ̈ıve Bayes.
