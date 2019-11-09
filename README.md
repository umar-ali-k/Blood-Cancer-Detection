# Blood-Cancer-Detection
The purpose of this project is to develop a system that can automatically detect cancer from the blood cell images
This system uses a convolution network that inputs a bloodcell images and outputs whether the cell is infected with cancer or not.
The appearance of cancer in blood cell images is often vague, can overlap with other diagnoses, and can mimic many other benign abnormalities.
These discrepancies cause considerable variability among medical personnel in the diagnosis of cancer. Automated detection of cancer from blood cell images at the level of expert medical personnel would not only have tremendous benefit in clinical settings, it would also be invaluable in delivery of health care to populations with inadequate access to diagnostic imaging specialists.

# FEASIBILITY STUDY
The feasibility study activity involves the analysis of the problem and collection of all relevant information relating to the product. The main aim of the feasibility study activity is to determine whether it would be financially and technically feasible to develop the product.

## DATASET
Image used in this project were obtained from Kaggle dataset which is a public dataset available online . This dataset was divided into 2 classes. There was total 4961 training images where 2483 images were from healthy patients and 2478 images were from patients affected with blood cancer. We tested the model with total 1240 images 620 from each class. These images had resolution of 320*240. 

## WORKING OF CNN
We have implemented CNN for the feature extraction and classification of the blood
samples.
A CNN is a multilayered neural network with a special architecture to detect complex features in data. CNNs have been used in image recognition, powering vision in robots, text in images and for self-driving vehicles.
The CNN consist layer of neurons and it is optimized for two-dimensional pattern recognition. CNN has three types of layer namely convolutional layer, pooling layer and fully connected layer.
