
# CNN-dog-breed-classifier


Welcome to the Convolutional Neural Network (CNN) project of the Udacity Deep Learning Nanodegree. In this project I build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. given an image of a dog, the algorithm will identify an estimate of the canine's breed. If supplied an image of a human, the code will identify the resembling dog breed.

__Key words: CNN, glob, OpenCV, Classifier, VGG16, ResNet__


## Installation:
The original repository can be found under
'git clone https://github.com/udacity/deep-learning-v2-pytorch.git'

##### Instruction:
1. Download this repository

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location 'path/to/dog-project/lfw'.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Open the Jupyter notebook "dog_app.ipynb" and go through each section.

[image1]: ./images/dog_classification.PNG "Example for classification"


![Sample Output][image1]


## Key features
This project provides a code basis for some basic 

Step 0: Import Datasets demonstrates the easy use of the 'glob' library and its usage for large datasets
Step 1: Detect Humans uses the OpenCV's Haar feature-based cascade classifier as a pre-trained face detector
Step 2: Detect Dogs uses the pre-trained VGG-16 Model to identify the object contained in an image. This segment is interesting for its image preprocessing. It shows how to transform, crop and resize an given image to meat VGG-16 model requirements.#

Step 3: A classifier for dog-breed, which can be used as a code basis for any kind of image classification. This model is written by myself from scratch and received limited training.

Step 4: Maybe **the most interesting aspect of this project** is the implementation of a new classifier while using a pre-trained model like ResNet. This allows the usage of highly-trained and sophisticated deep networks for our own mischievous or good-hearted goals.

Step 5: Use a high sophisticated neural network for a funny 



Remember today its funny dog faces, tomorrow [its you](https://xkcd.com/2228/) (go visit xkcd.com!)

[image2]: ./images/machine_learning_captcha.png "Soon"
![The not so far future][image2]




```python

```
