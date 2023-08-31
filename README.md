# Brain Tumor MRI Dataset Preprocessing

This repository contains a Python script for preprocessing a Brain Tumor MRI dataset. The script identifies the bounding box of the brain and tumor in each image, crops the images, and saves the cropped volumes. The preprocessing is aimed at preparing data for training deep learning models, such as segmentation networks.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)

## Introduction

This script performs the preprocessing of a Brain Tumor MRI dataset by identifying the bounding box or region of interest (ROI) in each image, cropping the images to the ROI, and saving the cropped volumes. The main purpose of this preprocessing is to prepare the data for training deep learning models, specifically segmentation networks.

## Requirements

- Python 3.x
- Nibabel (`pip install nibabel`)

## Usage

1. Clone the repository:

   ```sh
   git clone https://github.com/aidl-fast/BrainTumor-ROI-Crop.git

2. Organize your dataset in the specified structure.

3. Update the paths in the script to match your dataset and desired output folder.

4. Run the script:

   ```sh
   python preprocess.py

## Results

After running the script, the cropped volumes will be saved in the specified output folder while maintaining the original filenames. The script will also display the bounding box dimensions and indices for your reference.
