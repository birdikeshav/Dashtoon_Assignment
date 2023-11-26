# Neural Style Transfer

## Overview

This repository contains an implementation of a Neural Style Transfer model using PyTorch. The model is designed to adapt the aesthetic of any art to a new, original artwork, mimicking the style of a chosen artist.

## Prerequisites

Before running the Jupyter Notebook (`Neural_Style_Transfer.ipynb`), ensure you have the following dependencies installed:

```bash
pip install torch torchvision matplotlib numpy pillow
```
# Dataset

Download two images for the content and style:

**Content Image:**
- Choose any image you want to apply the style to. Save it as `content.jpg`.

**Style Image:**
- Choose an image that represents the artistic style you want to apply. Save it as `style.jpg`.

Ensure that both images are in the same directory as the Jupyter Notebook.

# Running the Notebook

1. Open a terminal and navigate to the directory containing the Jupyter Notebook and the images.

2. Run the following command to start Jupyter Notebook:

   ```bash
   jupyter notebook Neural_Style_Transfer.ipynb
