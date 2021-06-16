# Traffic-Sign-Classification

## Introduction

Traffic sign classification is the process of automatically recognizing traffic signs along the road, including speed limit signs, yield signs, merge signs, etc. Being able to automatically recognize traffic signs enables us to build “smarter cars”.

Self-driving cars need traffic sign recognition in order to properly parse and understand the roadway. Similarly, “driver alert” systems inside cars need to understand the roadway around them to help aid and protect drivers.

Traffic sign recognition is just one of the problems that computer vision and deep learning can solve.

## Dataset

The dataset we’ll be using to train our own custom traffic sign classifier is the German Traffic Sign Recognition Benchmark (GTSRB).

The GTSRB dataset consists of 43 traffic sign classes and nearly 50,000 images.

## Implementation

-Loading our training and testing split from the GTSRB dataset

-Preprocessing the images

-Training our model

-Evaluating our model’s accuracy

-Serializing the model to disk so we can later use it to make predictions on new traffic sign data
