# Knee Osteoarthritis Grading Detection

##  Overview

This project focuses on detecting and grading knee osteoarthritis using X-ray images. The system classifies images into four severity levels: Normal, Mild, Moderate, and Severe.

##  Dataset

* Knee X-ray images
* Four classes:

  * Normal
  * Doubtful
  * Mild
  * Moderate
  * Severe
* Images are organized into class-specific folders for training

##  Methodology

* Image preprocessing (resizing, normalization)
* Training using Convolutional Neural Networks (CNN)
* Multi-class classification using softmax output

##  Model

* Built using TensorFlow/Keras
* Learns visual patterns from X-ray images
* Classifies severity levels of osteoarthritis

##  Results

The model can differentiate between various stages of osteoarthritis, with performance depending on dataset size and quality.

##  How to Run

1. Install dependencies
2. Open the notebook
3. Run all cells for training and testing

##  Files Included

* `knee_code(train).ipynb` → Model training notebook
* `knee_code(test).ipynb` → Model testing notebook
* `requirements.txt` → Python dependencies

##  Future Improvements

* Improve accuracy using deeper architectures (ResNet, EfficientNet)
* Add explainability (Grad-CAM)
* Deploy as a web-based diagnostic tool
