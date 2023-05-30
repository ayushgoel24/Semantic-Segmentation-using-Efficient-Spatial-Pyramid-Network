# Semantic Segmentation using Efficient Spatial Pyramid Network

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Issues](https://img.shields.io/github/issues/ayushgoel24/Semantic-Segmentation-using-Efficient-Spatial-Pyramid-Network.svg)](https://github.com/ayushgoel24/Semantic-Segmentation-using-Efficient-Spatial-Pyramid-Network/issues)
[![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-orange.svg)](https://github.com/ayushgoel24/Semantic-Segmentation-using-Efficient-Spatial-Pyramid-Network)

## Overview
Semantic segmentation plays a critical role in computer vision applications, enabling pixel-level understanding of images. The above model leverages an efficient spatial pyramid of dilated convolutions to address the challenges in this domain, providing superior performance with reduced computational complexity.


## Key Features
- <b>Efficient Spatial Pyramid</b>: ESPNet utilizes a spatial pyramid of dilated convolutions to capture multi-scale context information effectively. This architecture improves the accuracy and robustness of semantic segmentation models.<br/>
- <b>State-of-the-Art Performance</b>: By incorporating the ESPNet model, we achieved state-of-the-art results in semantic segmentation tasks, surpassing previous benchmarks in terms of accuracy and efficiency.<br/>
- <b>Open-Source Implementation</b>: This repository provides the complete code implementation of the ESPNet model, allowing researchers and practitioners to reproduce the results and further extend the model.


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