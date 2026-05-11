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
