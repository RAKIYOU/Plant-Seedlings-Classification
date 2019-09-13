Plant Seedlings Classification 
==============================
Introduction
--------------------
I am playing on Kaggle recently. There is an old kaggle competition for image classification, which is very friendly to beginners. We are provided a training dataset and a testing dataset of images of plant seedlings at various stages of grown. Each image has a filename that is its unique id. The dataset comprises 12 plant species. The goal of the competition is to create a classifier capable of determining a plant's species from a single photo.

## Datasets ##
Please find [Training data](https://www.kaggle.com/c/plant-seedlings-classification/download/train.zip) for training and validation, 
and also [Testing data](https://www.kaggle.com/c/plant-seedlings-classification/download/test.zip) for prediction here.
    
## Dependencies ##
> * Python 3.7.3

> * NVIDIA GeForce GTX 1080

> * PyTorch 1.0.1

## Results ##
About CNNs, we trained VGG11, ResNet18, ResNet34 and Densenet121. we got every good results from almost every neural network.
There was no big difference on accuracy, and we easily got 94% accuracy after training 20 epochs.
When training ResNet34 over 25 epochs, its accuracy arrived even higher (96.347%).

|CNNs        |epochs|accuracy|
|:-----------|:----:|-------:|
|VGG11       |20    |93.38%  |
|ResNet18    |20    |94.13%  |
|ResNet34    |25    |96.34%  |
|Densenet121 |20    |95.21%  |

## Acknowledgments ##
The datasets used in our experiments are from Aarhus University Department of Engineering Signal Processing Group.
And please find [the original page](https://www.kaggle.com/c/plant-seedlings-classification/overview) on Kaggle.
