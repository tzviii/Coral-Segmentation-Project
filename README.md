# Coral Segmentation Project

---

## Overview

### Data

The original dataset waas provided by Matan Yuval from the Marine Imaging Lab, Haifa University.

You can find it in folder ******************

### Data augmentation

The data consists of approximately 230 images labelled using LabelBox (www.LabelBox.com). This nnumber of images is not nearly enough to train a deep learning newral network. I use data augmentation in the code.

### Model

The model is based mostly on UNet and implemented in keras.

### Training

The model is trained for 30 epochs.

After 30 epochs, calculated accuracy is about 0.8. The results look good. The low accuracy is due to poor "ground truth" and actually shows bette results than the ground truth itself.


Loss function for the training is basically a multiclass crossentropy.

---

## How to use

### Edit according to your preferences and run Prediction.py

You will see the predicted results of test image in ************

### Dependencies

In order to use Keras Segmentation you will need:

* Keras>=2.0.0
* imgaug>=0.2.9
* opencv-python>=4.1.1.26
* tqdm

### Results

Use the trained model to do segmentation on test images, the result is statisfactory.
