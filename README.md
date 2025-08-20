# 🚗 Iranian License Plate Detection & Recognition

This project performs automatic detection, segmentation, and recognition of Iranian vehicle license plates using OpenCV, EasyOCR, and a custom-trained logistic regression classifier.

---

## 🎯 Features

- Detects license plate region using contour approximation  
- Applies bilateral filtering, edge detection, and Gaussian blur  
- Extracts and crops the plate area from the image  
- Reads Persian text using EasyOCR  
- Trains a logistic regression model to classify segmented plate digits  
- Visualizes segmentation and recognition results

---

## 🛠️ Technologies Used

- Python 3.10  
- OpenCV  
- EasyOCR  
- scikit-learn  
- NumPy  
- Matplotlib  
- imutils

---

## 📦 Installation

1. Install required packages:
pip install opencv-python easyocr scikit-learn imutils matplotlib

```bash
