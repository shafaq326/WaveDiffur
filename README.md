# WaveDiffUR Satellite Image Super Resolution

## Overview
This project enhances low-resolution satellite images using deep learning.

## Files Included
- dataset.py
- vit_isrgan.py
- wavelet_utils.py
- wavediffur.py
- losses.py
- train.py
- evaluate.py
- infer.py

## Requirements
pip install torch torchvision rasterio pywavelets torchmetrics

## How to Train
Run train.py to train the model.

## How to Run
Use infer.py to generate a super-resolved image from a new satellite image.
