# Sentiment Analysis of Climate Related Tweets

This repository takes 10,000+ SAR images of Venus labeled by if there is a volcano or not, the number of volcanoes, the 'type' of volcano and their radii. I create a convolutional neural network which first classifies an image as either having a volcano or not, then with another output of identifying the number of volcanoes. Both work well with over 90% accuracy.  

## Data

The data is not provided in this repository but is available here: https://www.kaggle.com/datasets/fmena14/volcanoesvenus

## Files

- CNN_Venus_Volcanoes_SAR.ipynb: ipython notebook which reads in the raw data, quality controls the images automatically and then trains a CNN on the resulting images and labels (see notebook for details).

## Use

To use this notebook and files, you need to download the data from the link above and install the anaconda environment provided using: 

`conda env create -f environment.yml`

Then you will need to download the data from the above link and the notebook should run as designed. Note, in some places I have commented out saving and loading the trained keras models. 




