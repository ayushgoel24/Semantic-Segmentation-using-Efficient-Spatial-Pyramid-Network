# Semantic Segmentation using Efficient Spatial Pyramid Network

## Overview
Semantic segmentation plays a critical role in computer vision applications, enabling pixel-level understanding of images. The above model leverages an efficient spatial pyramid of dilated convolutions to address the challenges in this domain, providing superior performance with reduced computational complexity.


## Structure of this repository

This repository is organized as:

- [training](/src/training/) This directory contains the source code for training the ESPNet-C and ESPNet models.
- [testing](/src/testing/) This directory contains the source code for evaluating the model on RGB Images.

## Results

The ESPNet-C model achieves mIoU of 70.0% on Cityscapes dataset.
The ESPNet model achieves mIoU of 70.0% on Cityscapes dataset.

<p float="left">
    <img src="./static/output/dataset_1.gif">
    <p align="center">Output from Dataset 1</p>
</p>
<br/>
<p float="left">
    <img src="./static/output/dataset_2.gif">
    <p align="center">Output from Dataset 2</p>
</p>
<br/>
<p float="left">
    <img src="./static/output/dataset_3.gif">
    <p align="center">Output from Dataset 3</p>
</p>