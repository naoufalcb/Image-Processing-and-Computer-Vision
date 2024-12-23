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

3. **CNN-Based Approach for Traffic Sign Recognition**
   - File: `CNN_based_Approach_for_Traffic_Sign_Recognition.ipynb`
   - **What it does:** Implements a Convolutional Neural Network (CNN) for classifying traffic signs from an image dataset.
   - **Key Steps:**
     - Preprocess and augment the dataset of traffic sign images.
     - Train a CNN model for traffic sign classification.
     - Evaluate the model's performance on test data.

4. **HOG & SVM-Based Approach for Traffic Sign Recognition**
   - File: `HOG_&_SVM_based_Approach_for_Traffic_Sign_Recognition.ipynb`
   - **What it does:** Combines HOG features with a Support Vector Machine (SVM) classifier to recognize traffic signs.
   - **Key Steps:**
     - Extract HOG features from traffic sign images.
     - Train an SVM classifier on the extracted features.
     - Test the model and evaluate its accuracy.

5. **Pedestrian Recognition System**
   - File: `Pedestrian_Recognition_System.ipynb`
   - **What it does:** Develops a system to recognize pedestrians in images using image processing techniques and machine learning.
   - **Key Steps:**
     - Preprocess pedestrian images for consistent input size.
     - Extract relevant features and train a recognition model.
     - Evaluate the system's performance in detecting pedestrians.

6. **Clustering in Image Processing**
   - File: `Clustering_in_Image_Processing.ipynb`
   - **What it does:** Explores clustering techniques for image segmentation and grouping similar pixels or image patches.
   - **Key Steps:**
     - Preprocess images to extract relevant features for clustering.
     - Apply clustering algorithms (e.g., K-means, DBSCAN) to segment the image.
     - Visualize the clustering results to demonstrate segmentation effectiveness.

## Techniques Covered
1. **Histogram of Oriented Gradients (HOG):**
   Extracts key image features by analyzing gradients and their orientation.
2. **Image Preprocessing:**
   Includes resizing, color conversion, and preparing images for further analysis.
3. **Pixel-Level Manipulation:**
   Provides direct control over image pixel values, useful for filtering or annotation.
4. **Convolutional Neural Networks (CNN):**
   Applies deep learning techniques for image classification tasks.
5. **Support Vector Machines (SVM):**
   Utilizes HOG features with SVM for image classification.
6. **Clustering Algorithms:**
   Groups similar data points, useful in tasks like image segmentation.

## Prerequisites
- Python 3.8 or higher
- Required libraries are listed in `requirements.txt`.

## How to Run on Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the desired notebook (`.ipynb` file) by selecting **File > Upload notebook**.
3. Upload the repository files to your Google Drive or directly to Colab:
   - Use the following code snippet in a new Colab cell to clone the repository:
     ```python
     !git clone https://github.com/naoufalcb/Image-Processing-and-Computer-Vision.git
     ```
4. Navigate to the desired notebook within the repository directory in Colab's file explorer.
5. Install the dependencies:
   ```python
   !pip install -r Image-Processing-and-Computer-Vision/requirements.txt
   ```
6. Run the notebook cells interactively in Colab.

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/naoufalcb/Image-Processing-and-Computer-Vision.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd Image-Processing-and-Computer-Vision
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```
