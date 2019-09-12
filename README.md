Plant Seedlings Classification 
==============================
Problem discritation
--------------------
I am playing on kaggle recently. There is an old kaggle competitions for image classificiation, which is very friendly to beginners. we are privided a training set and a testing set of images of plant seedlings at various stages of grown. Each image has a filename that is its unique id. The dataset comprises 12 plant species. The goal of the competition is to create a classifier capable of determining a plant's species from a photo

## Datasets ##
Please find [Training data](https://www.kaggle.com/c/plant-seedlings-classification/download/train.zip)
and
[Testing data](https://www.kaggle.com/c/plant-seedlings-classification/download/test.zip) here.
    
## Requirements ##
Python 3.7.3

NVIDIA GeForce GTX 1080

PyTorch 1.0.1

## Results ##
About CNNs, we trained VGG11, ResNet18, ResNet34 and Densenet121. we got every good results from amost every neural networks.
There was no big difference on accuracy, and we easily got 94% accuracy after trainingt 20 epochs.
Among them, when  when training ResNet34 over 25 epochs, the accuracy became even higher (96.347%).

## Acknowledgments ##
The datasets used in our experiments Aarhus University Department of Engineering Signal Processing Group.
And please find the original [challenge page](https://www.kaggle.com/c/plant-seedlings-classification/overview) on Kaggle.
