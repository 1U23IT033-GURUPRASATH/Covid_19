# Covid_19
# COVID-19 Image Classification Using CNN

## 1. Project Overview
This project uses Convolutional Neural Networks (CNN) to classify medical images into two categories: COVID and Normal.

## 2. Problem Statement
The project aims to develop a deep learning model that can identify COVID-19 and Normal images using image classification techniques.

## 3. Objective
- To load and preprocess COVID-19 image datasets.
- To visualize and analyze the image data.
- To build two CNN models.
- To train and evaluate the models.
- To compare model performance using accuracy and recall.

## 4. Dataset Description
- Total Images: 251
- COVID Images: 111
- Normal Images: 140
- Image Size: 128 × 128
- Image Channels: 3 (RGB)
- Classes: COVID and Normal

## 5. Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn

## 6. Data Preprocessing
- Loaded image and label datasets.
- Converted labels into numerical values.
- Split the dataset into training, validation, and testing sets.
- Normalized image pixel values between 0 and 1.

## 7. Model Development

### CNN Model 1
- Three Convolutional layers.
- Max Pooling layers.
- Flatten layer.
- Dense layer.
- Sigmoid output layer.

### CNN Model 2
- Two Convolutional layers.
- Max Pooling layers.
- Flatten layer.
- Two Dense hidden layers.
- Sigmoid output layer.

## 8. Model Evaluation
The models are evaluated using:
- Training Accuracy
- Validation Accuracy
- COVID Recall
- Test Accuracy
- Test Recall

## 9. Result
CNN Model 2 achieved:
- Training Accuracy: 100%
- Validation Accuracy: 97.37%
- COVID Recall: 100% on training and validation sets.

## 10. Conclusion
This project demonstrates how CNN models can classify COVID and Normal images. Two CNN architectures were developed and compared. The results show that CNN can be used for educational image classification experiments.

**Note:** This project is for educational purposes only and is not a replacement for professional medical diagnosis.
