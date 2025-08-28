# Diabetic-Eye-Retinopathy 👁️🩺
- This project applies Deep Learning to detect Diabetic Retinopathy (DR) from retinal fundus images. Using state-of-the-art CNN architectures and optimizers, the goal is to improve early diagnosis and classification accuracy of DR, helping in preventing vision loss among diabetic patients.

## 📌 Problem Statement
- Diabetic Retinopathy is a leading cause of blindness worldwide. Early detection is critical, but manual screening is time-consuming and error-prone. This project automates DR detection using Convolutional Neural Networks (CNNs) to analyze retinal images.

## 🛠️ Models Implemented
- MobileNetV3
- EfficientNetB0
- InceptionV3
- ResNet152 (with different optimizers: Adam, Adamax, Nadam, RMSprop)

## 📂 Repository Structure
### Diabetic-Eye-Retinopathy/
- │── MobileNetV3.ipynb              # Training with MobileNetV3
- │── efficientnetB0.ipynb           # Training with EfficientNetB0
- │── inceptionv3.ipynb              # InceptionV3 baseline
- │── inceptionv3__.ipynb            # InceptionV3 variation
- │── inceptionv3_enh.ipynb          # InceptionV3 with enhancements
- │── resnet152ADAM.ipynb            # ResNet152 with Adam optimizer
- │── resnet152ADAM1.ipynb           # ResNet152 Adam variant
- │── resnet152ADAMAX.ipynb          # ResNet152 with Adamax optimizer
- │── resnet152NADAM.ipynb           # ResNet152 with Nadam optimizer
- │── resnet152RMSPROP.ipynb         # ResNet152 with RMSprop optimizer
- │── README.md                      # Project documentation

## 📊 Evaluation Metrics
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC curves
- Confusion Matrices

## 🎯 Results (Highlights)
- Tested multiple CNNs with different optimizers
- Comparative analysis of architectures
- Trade-off between model size, training time, and accuracy

## 📑 Future Enhancements
- Apply Transfer Learning with fine-tuning
- Use Ensemble Models for better accuracy
- Deploy model as a web/mobile application for real-time diagnosis
- Expand dataset for higher generalization

## 🤝 Contributing
- Contributions are welcome! You can improve models, add visualizations, or help deploy the project as an app.
