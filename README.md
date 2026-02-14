# Image Stitching using SIFT (Scale-Invariant Feature Transform)

Final Project – Computer Vision  
Zahra Syifaul - 442023618009 

---

## 📌 Project Description

This project implements an image stitching system using the Scale-Invariant Feature Transform (SIFT) algorithm.  
The goal is to combine two overlapping images into a single panoramic image by detecting, matching, and transforming image features.

The system demonstrates:
- Keypoint detection using SIFT
- Feature descriptor extraction
- Feature matching with Lowe’s Ratio Test
- Homography estimation using RANSAC
- Perspective warping and panorama generation

---

## 🧠 Method Overview

The stitching pipeline consists of the following steps:

1. Convert images to grayscale
2. Detect keypoints using SIFT
3. Extract feature descriptors
4. Perform feature matching using BFMatcher
5. Apply Lowe's Ratio Test to filter good matches
6. Estimate homography matrix using RANSAC
7. Warp perspective transformation
8. Merge images into final panorama

---


---

## ⚙️ Requirements

Make sure Python 3.8+ is installed.

Install required libraries:

```bash
pip install opencv-python opencv-contrib-python numpy matplotlib



