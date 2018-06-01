# Capstone-Food Classifiaction.
Food recognition is a key element in the food consumption monitoring.There are few traditional techniques in recognizing the food like referring to nutrition facts or Amazon turk.Lately, Deep learning techniques are being used to classify the food. Food recognition is a unique object recognition, it is becoming most active topic in computer vision lately. The specific part is that dish classes have a much higher inter-class similarity and intra-class variation than usual ImageNet objects (cars, animals, rigid objects, etc.).
Food are different in different parts of the world;the color,shape and texture makes it interesting to classify them.

## Datasets

Dataset: https://www.vision.ee.ethz.ch/datasets_extra/food-101/)

The dataset which we will be using for this project is 11 categories extracted from Food-101,which has 101 food categories.
Each category has around 750 images in training dataset and 250 images in test dataset.We have further separated training dataset into 7235 images and 1015 images in training and validation datasets respectively.
The food-101 is large dataset and has 1M images,it would take high computational cost and time to evaluate the whole dataset,So We extracted first 11 categories from that dataset.

Project Requirements
Python 3.5
Tensorflow 1.4.0
Keras 2.0 with tensorflow as backend.
