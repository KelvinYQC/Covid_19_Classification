# Project to Classify Covid-19 X-ray Images Leverage Deep Learning

## Dataset:

[CoronaHack -Chest X-Ray-Dataset](https://www.kaggle.com/datasets/praveengovi/coronahack-chest-xraydataset)

## Problems:

The dataset that we are working with originates from the Kaggle repository titled 'Coronahack - Chest X-Ray-Dataset', which aims to aid in the development of Machine Learning models that can effectively identify COVID-19 cases using chest X-Ray images. The dataset encompasses a vast collection of chest X-ray images from both healthy individuals and patients affected by various respiratory conditions, including COVID-19 (Pneumonia), SARS (Severe Acute Respiratory Syndrome), Streptococcus, and ARDS (Acute Respiratory Distress Syndrome).

The significance of this dataset stems from the context of the ongoing global COVID-19 pandemic. The virus primarily affects the respiratory system, with chest X-ray serving as one of the vital imaging methods to detect the virus. Thus, our project aims to leverage this dataset to solve two main problems: a binary classification task to distinguish between COVID-19 and healthy X-ray images, and an image denoising task to improve the image quality for more accurate analysis.

The metadata for each image, including the labels indicating the presence of specific conditions, is provided in a CSV file named 'Chest_Xray_Corona_Metadata.csv'. The use of such labelled dataset enables the implementation of supervised learning algorithms for this deep learning project.

Through our project, we hope to contribute to the faster and more accurate diagnosis of COVID-19, thereby enhancing the efficiency of medical response to the pandemic.

## EDA:

- Summarize data: record counts, missing values
- Visualize the raw dataset using charts and tables (line/bar charts, q-q plots, heatmaps, violin, etc.)
- Image Data: Histograms, samples, outliers
- Normalize data (equalizer?)
- Scale the image to the same size

## Models:

- Image Denoising
- Denoising Autoencoders (DAE)
- Deep Image Prior: Deep Image Prior Kaggle
- Covid Classification
- Sequential model (CNN)
- Transfer Learning (ResNet): Kaggle ResNet

## Tasks

Begin draft report

Run models

Tune Autoencoder
