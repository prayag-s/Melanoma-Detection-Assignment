# Melanoma Detection Assignment

   <p align="right">By Prayag Sanjay</p>

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


## Conclusion

  1. The model has achieved maximum validation accuracy of 77%
     **which is an improvement over the previous models by 20%.**


  2. There is less overfitting than before  as training and validation
     accuracy are closer than before. The accuracy for both training and validation decrease gradually together.


  3. The loss for both training and validation decrease gradually together as well.


  4. So we can conclude the **after reducing class imbalance**,
     the **accuracy has increases significantly** and also **overfitting is under check** as well.


  5. So overall we can conclude that for a case where the number of training
     data is less, following needs to be employed.

    Augementation


    Adding more data using augementatino pipeline


    Adding dropout layer to reduce overfitting
