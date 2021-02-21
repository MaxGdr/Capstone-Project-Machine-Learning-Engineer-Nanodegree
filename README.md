# Capstone-Project-Machine-Learning-Engineer-Nanodegree


# Capstone Proposal
This repo expose my Capstone Project Proposal for my ML Engineer Nanodegree at Udacity : *Image colorization*

To get hyperlinks on references I've done, please download it.

# Capstone Project

My Capstone Project is explained in [this file](https://github.com/MaxGdr/Capstone-Project-Machine-Learning-Engineer-Nanodegree/blob/main/Capstone%20Project%20-%20Image%20Colorization.pdf
)

You can also find in this repository my Notebook to train a Generative Adversarial Network, to colorize grayscale images.

# Get Started 

This GAN has been built with Pytorch. Feel free to re-code it in Tensorflow if you prefer. 

## Install dependencies

To install dependencies, you just have to install libraries from requirements.txt

```bat
pip install -r requirements.txt
```

## Download COCO Dataset

I'm using FASTAI Package to download the COCO Dataset (Dataset used to train GAN).
There is a cell to do it directly in the notebook.

## Hardware

To train this model, I used a Tesla V100 32GB, and it tooks 9 hours. 

You can train it on CPU, but I highly recommend to use GPU.

## After train

You can try model with visualize method to predict and generate images from validation Dataset.
