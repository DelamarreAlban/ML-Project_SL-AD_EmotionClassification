# Detection of Emotion and AUs Using Facial Images
Stephanie Lunn and Alban Delamarre
CAP5610: Machine Learning
Fall 2018

## Objective
Using a dataset called the Extended Cohn-Kanade Dataset (CK+), we used machine learning for the analysis of 593 sequence images taken across 123 subjects to identify the target emotional category depicted by the faces in the image. The emotion categories assessed include seven potential outcomes, specifically anger, contempt, disgust, fear, happy, sadness, and surprise. Using Support Vector Machine (SVM), Convolutional Neural Networks (CNN), and Transfer Learning with Inception-v3, we aim to obtain accuracy similar to related image work in the field, on the CK+ dataset. 

## Files Included
For preprocessing, the following programs are required:
 * ML-Project_SL-AD_AU-FaceCrop.ipynb
 * ML-Project_SL-AD_AUs-Sorting.ipynb

To apply SVM to the dataset, the following program is required:
 * ML-Project_SL-AD_SVM.ipynb

To apply CNNs to the dataset, the following programs are required:

#### For Emotion Detection Directly from Images:
 * ML-Project_SL-AD_EMO-CNN.ipynb

#### For AU Detection Directly from Images Before Detecting AUs:
 * ML-Project_SL-AD_AU2EMO-CNN.ipynb

To apply Inception-v3 to the dataset, the following program is required:
 * ML-Project_SL-AD_TransferLearning_InceptionV3.ipynb

## Important Notes
In order to rerun these files, must revise the paths for the dataset location to appropriate access path. Also, the image size parameters must be changed to either 48 x 48 or 299 x 299 depending on which experiment you would like to recreate.