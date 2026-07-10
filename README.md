Markdown
# 🔍 Content-Based Image Retrieval (CBIR) System

![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=flat&logo=opencv&logoColor=white)

## 📌 Introduction
This project implements a **Content-Based Image Retrieval (CBIR)** system. Given an input query image (e.g., lions, tigers, foxes), the system converts the image into a feature vector and efficiently searches for the most visually similar images within a dataset using vectorization methods.

## 📂 Project Structure
```text
CBIR_byHieu/
├── dataset/                 # Directory containing animal images
├── src/
│   ├── store_vectors.py     # Script to extract and save image feature vectors
│   └── search_image.py      # Script to search for similar images
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
