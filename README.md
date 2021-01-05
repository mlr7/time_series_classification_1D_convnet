# time_series_classification_1D_convnet
1D convolutional neural network for time series classification on pitch velocity sequencing data.

## Introduction

## Data

## Model

The basic idea of convolutional neural networks is to perform automated feature extraction before feeding the data into a dense feedforward neural network for classification or regression. Convolutional layers extract features from data by passing filters over the input data to form feature maps. This process works with both one, two, and higher dimensional data. 

2D convolutions encode spatial invariance. 1D convolutions encode temporal invariance. 

The success of a 1D convnet will depend on the nature of the dataset being modeled. For time series data containing long range dependencies, LSTM recurrent neural networks often can achieve higher accuracy than 1D convnets, but at the price of higher training time. See [Chollet,2018, chpt. X] for a discussion of the merits of 1D convnets versus LSTM architectures. 

## Model Evaluation

## Discussion

## Next Steps
