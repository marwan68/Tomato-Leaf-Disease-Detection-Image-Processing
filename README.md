# Tomato Leaf Disease Spot Detection Using Image Processing

## Project Overview

This project detects suspected disease spots on tomato leaf images using classical image processing techniques. The system does not use any machine learning model or deployment. The dataset contains healthy and diseased tomato leaf images. Before processing, the dataset was cleaned by removing corrupted, duplicate, blurry, and unclear images. The images were then processed using preprocessing, filtering, segmentation, edge detection, and contour detection to highlight suspected disease regions.

## Project Aim

The aim of this project is to detect and highlight visible disease-like spots on tomato leaves using image processing only.

## Problem Statement

Tomato leaf diseases often appear as dark, brown, or damaged spots on the leaf surface. Manual detection depends on human observation and may take time. This project uses image processing techniques to automatically detect and highlight suspected diseased regions.

## Dataset

The dataset contains approximately 200 tomato leaf images divided into two categories:

- Healthy_Tomato
- Diseased_Tomato

Before preprocessing, the dataset was prepared and cleaned. Corrupted images, duplicate images, blurry images, and unclear images were removed. The full dataset was processed in Google Colab. Only sample screenshots and sample output images are included in this repository to keep it clean.

## Tools Used

- Python
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- Google Drive
- GitHub

## Methodology

The project follows these steps:

1. Dataset Collection
2. Dataset Cleaning
3. Image Preprocessing
4. Image Filtering
5. Segmentation
6. Edge Detection
7. Contour Detection
8. Final Output Generation

## Image Processing Pipeline

```text
Input Tomato Leaf Image
        ↓
Dataset Cleaning
        ↓
Preprocessing
        ↓
Filtering
        ↓
Segmentation
        ↓
Edge Detection
        ↓
Contour Detection
        ↓
Final Output
```

## Dataset Preparation

The original tomato leaf images were checked before processing. The dataset preparation step included:

- Checking if images could be opened correctly
- Removing corrupted or unreadable images
- Removing duplicate images
- Removing blurry or unclear images
- Organizing valid images into Healthy_Tomato and Diseased_Tomato folders

## Preprocessing

The preprocessing stage included:

- Resizing images to 500 × 500 pixels
- Converting images to grayscale
- Applying contrast enhancement
- Normalizing image values

## Filtering

The filtering stage was used to reduce noise and improve image quality. Gaussian blur was applied to smooth the image. Median filtering and sharpening were also used for demonstration and comparison.

## Segmentation and Edge Detection

In the segmentation stage, the leaf region was separated from the background. Then suspected disease regions were detected inside the leaf area. Morphological operations were applied to clean the mask. Canny edge detection was used to detect boundaries, and the detected edges were improved for better visualization. Finally, contours and bounding boxes were drawn around the detected disease regions.

## Sample Results

### Dataset Samples

<img src="screenshots/00_dataset_samples.png" width="700">

### Preprocessing Result

<img src="screenshots/01_preprocessing_result.png" width="700">

### Filtering Result

<img src="screenshots/02_filtering_result.png" width="700">

### Segmentation and Edge Detection Result

<img src="screenshots/03_segmentation_edge_result.png" width="700">

## Sample Final Outputs

Sample final output images are included in the `sample_outputs` folder.

### Final Output 1

<img src="sample_outputs/final_output_01.jpg" width="500">

### Final Output 2

<img src="sample_outputs/final_output_02.jpg" width="500">

### Final Output 3

<img src="sample_outputs/final_output_03.jpg" width="500">

## Folder Structure

```text
Tomato-Leaf-Disease-Detection-Image-Processing/
│
├── README.md
├── Tomato_Leaf_Disease_Detection_Image_Processing.ipynb
│
├── screenshots/
│   ├── 00_dataset_samples.png
│   ├── 01_preprocessing_result.png
│   ├── 02_filtering_result.png
│   └── 03_segmentation_edge_result.png
│
└── sample_outputs/
    ├── final_output_01.jpg
    ├── final_output_02.jpg
    └── final_output_03.jpg
```
