# PyTorch Image Classifier 🔥
*(simple code architecture to understand)*

![pytorch](https://img.shields.io/badge/1.12.1-torch-red?logo=pytorch&logoColor=white)
![python](https://img.shields.io/badge/3.7.x-python-blue?logo=python&logoColor=white)

## Overview

An *image classifier* is a machine learning model that recognizes images. When you give it an image, it responds with a category label for that image.

	image:🌠 -> model:🤖 -> answer:"star"

You train the image classifier by showing it many examples of images that you have already labeled. For example, you can train an image classifier to separate cats and dogs.
	
	images:(🐶🐱🐶🐱) -> train:🧠 -> model:🤖

After the training of the image classifier is complete, you evaluate its accuracy and if it performs well enough, save it as a model (.pth) file. You can then use the image classifier model in your code.


## Organize Your Training Data

Prepare the training dataset by sorting the images into subfolders or download the pre-made one from Kaggle. Give each subfolder a name for the category of images it contains. Here is an example structure for classifying cats and dogs:

> **train**
>> cat
>>> img1.jpg\
>>> ...\
>>> imgN.jpg

>> dog
>>> img1.jpg\
>>> img2.jpg\
>>> ...\
>>> imgN.jpg

> **test** *(same as in train, but own images)*

> **validation** *(same as in train, but own images)*

And then in the code you will need to specify the path to the directory where 3 folders are located *(train, test, validation)*


## Work with project

There are only 2 important files in this repository

- **requirements.txt**- all important python libraries.
- **torch-ok.ipynb** *(named to understand that PyTorch is ok)* - in the book, you can step by step launching a cell to create your own classification neural network.

❗️Before you start, you must have the [Python](https://www.python.org/downloads/) programming language version 3.7 installed.\
 After it is important to install all the necessary libraries, go from the directory to the terminal and write the command `pip3 install -r -U requirements.txt`. Then write command `jupyter notebook` to open the Jupyter notebook and open `torch-ok.ipynb` file.

Having entered the file with the notebook itself, you will see a comment explaining this or that action. Good luck!

\
\
*🌟 If it helped you, you can star my repository.*

