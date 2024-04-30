# DA-623 Assignment

Name: Sarthak Diwan

Roll No: 200123076

## Description

Comparison between PCA, Gram-Schmidt, and DFT by applying and approximating images. 

## Comparison
![Video](CompressionComparison.mp4)
We observe that PCA gives a clear image very early, but some pixels are just very off. After about 512x200 it seems visually difficult to distinguish between the original and PCA compressed image.

DFT also gives a clear image but the brightness or color accuracy isn't good. It looks more like a filtered image.

Gram-Schmidt gives a decent image after a minimum 512x450 subspace, even then it is very poor.


## Installation
To make animation video `manim` is required. Refer to its installation [here](https://docs.manim.community/en/stable/installation.html). 

Rest of the packages required are in the first cell of the notebook (`numpy`, `matplotlib`, `scikit-learn`).

## Usage

Run the `notebook.ipynb` in a jupyter notebook environment. 
It contains the tutorial as well as the code to generate the animation.


testing.ipynb contains code for grayscale image approximation.
