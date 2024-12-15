# Image Processing and Computer Vision

This repository contains Jupyter notebooks showcasing foundational algorithms and techniques in image processing and computer vision using Python.

## Contents

### Notebooks
1. **HOG Descriptor and Feature Extraction**
   - File: `HOG_Descriptor_Feature_Extraction.ipynb`
   - **What it does:** Implements the Histogram of Oriented Gradients (HOG) algorithm, a popular technique for extracting features from images. This is often used in object detection tasks.
   - **Key Steps:**
     - Resize an image to 64x128 pixels for consistent processing.
     - Compute the HOG descriptor, which captures edge directions and intensity.
     - Visualize the resulting feature vector.

2. **Image Loading and Pixel Manipulation**
   - File: `Image_Loading_Color_Manipulation.ipynb`
   - **What it does:** Demonstrates basic image processing tasks, such as loading images, accessing pixel values, modifying them, and converting color spaces.
   - **Key Steps:**
     - Load an image using OpenCV and display it with Matplotlib.
     - Access and change pixel values to manipulate the image.
     - Convert image color spaces (e.g., BGR to RGB).

## Techniques Covered
1. **Histogram of Oriented Gradients (HOG):**
   Extracts key image features by analyzing gradients and their orientation.
2. **Image Preprocessing:**
   Includes resizing, color conversion, and preparing images for further analysis.
3. **Pixel-Level Manipulation:**
   Provides direct control over image pixel values, useful for filtering or annotation.

## Prerequisites
- Python 3.8 or higher
- Required libraries are listed in `requirements.txt`.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Image-Processing-and-Computer-Vision.git
