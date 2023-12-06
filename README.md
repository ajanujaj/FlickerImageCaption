# Image Captioning with ResNet34 and Attention Mechanism

## Overview

This project implements an image captioning model using PyTorch. The architecture consists of a ResNet34-based feature extraction model, a decoder with GRU cells, and an attention mechanism.

## Dataset

The dataset used for training and evaluation is the Flickr8k dataset, available at [this Kaggle link](https://www.kaggle.com/datasets/adityajn105/flickr8k).

## Pretrained Model

The feature extraction model utilizes a pretrained ResNet34 model.

## Code Structure

- `FeatureExtraction`: ResNet34-based feature extraction class.
- `cleancaption`: Function for cleaning and preprocessing captions.
- `Vocabulary`: Class for managing word-to-index mapping.
- `Attention`: Attention mechanism class.
- `Decoder`: Decoder model with GRU cells and attention.

## Dependency 
- PyTorch
- torchvision
- Other standard Python libraries
