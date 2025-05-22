# pdf-photo-extractor
Extracts photo-like images from PDF pages using Python and OpenCV
# 📸 PDF Photo Extractor
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PyMalama/pdf-photo-extractor/blob/main/photo_extractor_colab.ipynb)


This project automatically extracts **photo-like images** from a PDF document, even when the images are not embedded but are instead part of vector-rendered or scanned pages.

## ✅ Features

- Converts PDF pages to high-resolution images
- Uses OpenCV to detect and crop actual photo regions
- Downloads all cropped images as a ZIP file
- Runs smoothly in Google Colab

## 🚀 Getting Started

1. Open the [Colab notebook]https://colab.research.google.com/drive/1yqO_JnKOQPqOUbIp0hg8ULuKG_exqrdd?usp=sharing.
2. Upload your PDF.
3. The notebook detects and crops image-like areas.
4. Download the ZIP of extracted images.

## 📦 Requirements

- `pdf2image`
- `opencv-python-headless`
- `poppler-utils` (for Linux/Colab)

You can install dependencies using:

```bash
pip install pdf2image opencv-python-headless
sudo apt-get install poppler-utils

