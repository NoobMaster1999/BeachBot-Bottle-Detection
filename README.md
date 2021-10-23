<img src="https://github.com/ArunMichaelDsouza/tensorflow-image-detection/raw/master/icon.png" width="250" height="auto" alt="tensorflow-image-detection icon"/>

# tensorflow-image-detection

A generic image detection program that uses Google's Machine Learning library, [Tensorflow](https://www.tensorflow.org/) and a pre-trained Deep Learning Convolutional Neural Network model called [Inception](https://research.googleblog.com/2016/03/train-your-own-image-classifier-with.html).

This model has been pre-trained for the [ImageNet](http://image-net.org/) Large Visual Recognition Challenge using the data from 2012, and it can differentiate between 1,000 different classes, like Dalmatian, dishwasher etc.
The program applies Transfer Learning to this existing model and re-trains it to classify a new set of images.

This is a generic setup and can be used to classify almost any kind of image. I created a small demo that classifies two image data sets - my photos and my girlfriend's photos, and returns a prediction score denoting the possibility of it being my image or my girlfriend's image.

<br/>

## Installation
Make sure you have [Python 3](https://www.python.org/downloads/) installed, then install [Tensorflow](https://www.tensorflow.org/install/) on your system, and clone this repo.

<br/>

### Prepare the image data sets
In order to start the transfer learning process, a folder named ``training_dataset`` needs to be created in the root of the project folder. This folder will contain the image data sets for all the subjects, for whom the classification is to be performed.

[Download the Datasets here](https://drive.google.com/drive/folders/1ujZ-Vi9X9CoS20dgXDmBNgUrc3cyUnXI?usp=sharing)
