CNN -Landscape Classifier
============

This is a Convolutional Neural Network(CNN) based on keras, tensorflow.
This Model classifies images to 6 different categories - buildings, forest, glacier, mountain, sea, street.
There are images which has both buildings and streets, or a mountain in a forest which cannot be classified to 1 category,
so it is not possible to get an absolute accurate model. Still, this model has an accuracy of about 82% (Train & Test)


## About Dataset

This Dataset is from https://www.kaggle.com/puneet6060/intel-image-classification.
It contains around 14k train images and 3k test images of resolution 150x150


## About Model
- About 82% Train & Test Accuracy.
- No overfitting issues
- About 83,000 total parameters

## Repository Structure
```
┣ 📂datasets
┃  ┗ source.txt
┃  ┗Intel Image Classification  (Download dataset and extract it here)
┣ Landscape Classifier.ipynb
┣ Landscape-Classifier.h5
┣ README.md
```
