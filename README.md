# image-classifier
built an image classifier to recognize different species of flowers

## Project Information
Going forward,AI algorithms will be incorporated into more and more everyday applications. For example, you might want to include an image classiﬁer in a smart phone app. To do this, you’d use a deep learning model trained on hundreds of thousands of images as part of the overall application architecture. A large part of software development in the future will be using these types of models as common parts of applications. 

In this project,you’ll train an image classiﬁer to recognize different species of ﬂowers. You can imagine using something like this in a phone app that tells you the name of the ﬂower your camera is looking at. In practice you’d train this classiﬁer, then export it for use in your application. We’ll be using this dataset of 102 ﬂower categories.

## Tools Used
The Code is written in Python 3.6.6 . If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip.

* Install pip run in the command Line`python -m ensurepip -- default-pip`
* Upgrade it`python -m pip install -- upgrade pip setuptools wheel`
* Upgrade Python`pip install python -- upgrade`

Python libiraries used:
* Numpy
* Pandas 
* Matplotlib
* Pytorch
* PIL
* Json

`pip install numpy pandas matplotlib pil` or `conda install numpy pandas matplotlib pil`

## Json File
In order for the network to print out the name of the flower a .json file is required. If you aren't familiar with json you can find information [here](https://www.json.org/). By using a .json file the data can be sorted into folders with numbers and those numbers will correspond to specific names specified in the .json file.

## GPU
As the network makes use of a sophisticated deep convolutional neural network the training process is impossible to be done by a common laptop. In order to train your models to your local machine you have three options

1.<strong>_Cuda_</strong> -- If you have an NVIDIA GPU then you can install CUDA from [here](https://developer.nvidia.com/cuda-downloads). With Cuda you will be able to train your model however the process will still be time consuming

2.<strong>_Cloud Services_</strong> -- There are many paid cloud services that let you train your models like [AWS](https://aws.amazon.com/fr/) or [Google Cloud](https://cloud.google.com/)

3.<strong>_Coogle Colab_</strong> -- [Google Colab](https://colab.research.google.com/) gives you free access to a tesla K80 GPU for 12 hours at a time. Once 12 hours have ellapsed you can just reload and continue! The only limitation is that you have to upload the data to Google Drive and if the dataset is massive you may run out of space.
