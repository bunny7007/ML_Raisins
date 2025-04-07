# ML_Raisins
# Image Processing with OpenCV

This project performs basic image processing operations using OpenCV, such as converting to grayscale, binary thresholding, inversion, and contour detection.

## 🚀 Features

- Load and display images using OpenCV
- Convert images to grayscale and binary format
- Invert binary images
- Detect and draw contours
- Display intermediate processing steps

## 📂 Folder Structure

# Raisin Classification with SVM

This project uses Support Vector Machines (SVM) to classify raisin varieties ("Kecimen" and "Besni") based on their morphological features. The classification is done using both polynomial and RBF (Radial Basis Function) kernels. The dataset is sourced from a `.xlsx` file and includes preprocessing, model training, cross-validation, and visualization of results.

## 📊 Dataset

- **File:** `Raisin_Dataset.xlsx`
- **Classes:** Kecimen (0), Besni (1)
- **Features:** Area, Perimeter, MajorAxisLength, MinorAxisLength, Eccentricity, ConvexArea, Extent, etc.

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `openpyxl` (for reading Excel files)

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/raisin-svm-classification.git
   cd raisin-svm-classification
