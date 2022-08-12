# Cell_Nuclei_Image_Segmentation

# <div align="center">Cell Nuclei Image Segmentation</div>
<div align="center"><img src="https://github.com/WanNajmi/Cell_Nuclei_Image_Segmentation/blob/main/nuclei.jpg" width="80%"></div>

## Overview
This dataset contains a large number of segmented nuclei images. 
The images were acquired under a variety of conditions and vary in the cell type, magnification, and imaging modality (brightfield vs. fluorescence). 
The dataset is designed to challenge an algorithm's ability to generalize across these variations.

## Dataset:
[Kaggle - 2018 Data Science Bowl](https://www.kaggle.com/competitions/data-science-bowl-2018/data)

#### Dataset attributes:
Each image is represented by an associated ImageId. 
Files belonging to an image are contained in two folders with this ImageId. Within this folder are two subfolders
- Train : Inputs contain image file, Masks contain the segmented masks of each nucleus.
- Test : Inputs contain image file, Masks contain the segmented masks of each nucleus.
Each mask contains one nucleus. Masks are not allowed to overlap (no pixel belongs to two masks).

The train folder contains 603 images file for both folder while the test folder contains 67 images file for both folders.

## Data Exploration:

## Train Input Image:
<img src = "https://github.com/WanNajmi/Cell_Nuclei_Image_Segmentation/blob/main/TrainInput.png" width = "80%" >

## Train Mask Image:
<img src = "https://github.com/WanNajmi/Cell_Nuclei_Image_Segmentation/blob/main/TrainMask.png" width = "80%" >

## Test Input Image:
<img src = "https://github.com/WanNajmi/Cell_Nuclei_Image_Segmentation/blob/main/TestInput.png" width = "80%" >

## Test Mask Image:
<img src = "https://github.com/WanNajmi/Cell_Nuclei_Image_Segmentation/blob/main/TestMask.png" width = "80%" >
