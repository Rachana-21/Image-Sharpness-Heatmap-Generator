#  Image Sharpness Heatmap Generator 

This project computes and visualizes sharpness levels of images using Laplacian variance. It is useful for analyzing focus in photography, quality control, and preprocessing for computer vision tasks. Designed for use in Google Colab with images stored in Google Drive.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

##  Features

- Calculates pixel-level sharpness using Laplacian filters
- Generates a sharpness heatmap for each image
- Supports batch processing of multiple images in a folder
- Easy to customize thresholds, colormaps, and image source

---

##  Setup (Google Colab Instructions)

### 1. Upload this Notebook to Colab

> [Open in Colab](https://colab.research.google.com/)

### 2. Prepare Your Images

- Create a folder in your **Google Drive** called `sharpness_test_images`
- Upload your `.jpg` or `.png` images there

### 3. Mount Drive and Run

Paste and execute the following:

```python
from google.colab import drive
drive.mount('/content/drive')
