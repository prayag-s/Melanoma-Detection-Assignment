# Melanoma Detection Assignment

   <p align="right">By Prayag Sanjay</p>

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

## Problem Statement
  To build a CNN based model which can accurately detect melanoma. 

  Melanoma is a type of cancer that can be deadly if not detected early.
  It accounts for 75% of skin cancer deaths.

  A machine learning solution which can evaluate images and alert the
  dermatologists about the presence of melanoma has the potential to reduce
  a lot of manual effort needed in diagnosis.  sell at maximum profits.

  Hence,

  Goals of Study
  
  To build a multiclass classification model using a custom convolutional
  neural network in TensorFlow.


## Approach
  We will build a baseline CNN model first and tune it on the validation set.   

  We will check for underfitting / overfitting of  model and improve it using
  **Augmentation** of the training data.

  We will check for **class imbalance** of the  model and improve it generating
  more images of each class.	


## Conclusions

  1. The model has achieved maximum validation accuracy of 85%
     **which is an improvement over the previous models by 30%.**


  2. There is less overfitting than before  as training and validation
     accuracy are closer than before. The accuracy for both training and validation decrease gradually together.


  3. The loss for both training and validation decrease gradually together as well.


  4. So we can conclude the **after reducing class imbalance**, **tuning the learning rate**, 
     the **accuracy has increases significantly** and also **overfitting is under check** as well.


  5. So overall we can conclude that for a case where the number of training
     data is less, following needs to be employed.

    Adding more data using augementation pipeline


    Adding dropout layer to reduce overfitting
   
   
    Adding more layer to achieve more accuracy
    
     
    Tune learning rate for optimum accurany
    
## Technologies Used
   
    Tensorflow version 2.8.0
    Keras version 2.8.0
    
## Acknowledgements

    This project would not have been possible without 
        - Excellent lectures on Upgrad from IIIT-B profressors
        - My mentor Mr. Jain
        - My batchmates in October 2021 batch
        - SME Mr. Karmajit

## Contact
    Created by [@prayag-s] - feel free to contact me!

