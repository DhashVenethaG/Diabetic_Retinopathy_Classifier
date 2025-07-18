# Machine_Learning_Projects
# Diabetic Retinopathy Detection Using Custom CNN and XGBoost

This project presents a machine learning pipeline for detecting Diabetic Retinopathy (DR) from retinal fundus images. A custom Convolutional Neural Network (CNN) is used for deep feature extraction, and the features are classified using XGBoost. The model achieves 95% accuracy and includes a real-time user interface built with Gradio.

## Project Highlights

- Model: Custom CNN for feature extraction
- Classifier: XGBoost for final classification
- Accuracy Achieved: 95%
- Preprocessing Techniques:
  - CLAHE (Contrast Limited Adaptive Histogram Equalization) for enhancing image contrast
  - SMOTE (Synthetic Minority Oversampling Technique) for handling class imbalance
- Interface: Real-time prediction interface developed using Gradio

## Workflow Overview

1. **Preprocessing**
   - CLAHE applied to improve image quality
   - Images resized and normalized

2. **Feature Extraction**
   - Custom CNN extracts high-level features from fundus images

3. **Data Balancing**
   - SMOTE used to synthetically balance the dataset

4. **Classification**
   - XGBoost classifier trained on features extracted by CNN

5. **Deployment**
   - Gradio interface enables real-time image input and DR prediction


## Demo Video

A demo video showing the functionality, workflow, and results of the system is available at the following link:

[View Demo on Google Drive](https://drive.google.com/file/d/12QgD8ri5XoeNtxkOaZii4IXOB_o0cxxU/view?usp=drive_link)

## Technologies Used

- Python
- OpenCV
- TensorFlow / Keras
- XGBoost
- Imbalanced-learn (SMOTE)
- Gradio

## Contact

For any queries or collaboration opportunities, please feel free to reach out.
