
# Tree Cover Mapping with U-Net Transformer (UNETR) Using High-Resolution Satellite Imagery in PyTorch

This repository provides a complete deep learning workflow for tree cover mapping using semantic segmentation with the U-Net Transformer (UNETR) on high-resolution satellite imagery using PyTorch.



## Overview
Accurate tree cover mapping is important for environmental monitoring, urban planning, and climate studies. This project implements a UNETR deep learning model for semantic segmentation that combines:

•	Vision Transformer encoder for global contextual learning

•	CNN-based U-Net decoder for precise spatial reconstruction

The model predicts pixel-wise tree cover maps from satellite imagery.

## Dataset
Google Earth high-resolution RGB (3-band) imagery was used for tree mapping. The dataset consists of high-resolution Google Earth images with corresponding segmentation masks, each with a spatial size of 256 × 256 pixels. The masks contain three classes: tree, vegetation (all vegetation cover other than trees, such as grass, shrubs, and crops), and background (all other features, including water, built-up areas, and bare soil).
## Workflow
<img width="3205" height="2331" alt="Flow" src="https://github.com/user-attachments/assets/b9742a36-d9f8-4c85-9f89-dcaf804daa7a" />

## Results
<img width="1037" height="825" alt="Rr" src="https://github.com/user-attachments/assets/5f858067-4928-4ffa-95a0-f2b0f8cbc57c" />

## Contributing
I welcome contributions and feedback from the community. Feel free to open issues, propose enhancements, or submit pull requests to improve this project. If you have collaboration ideas, research suggestions, or would like to work together on related topics, please feel free to reach out..

