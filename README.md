# Brain-Tumor-Classification
A deep learning project using CNNs to classify brain MRI images as Tumor or No Tumor. Built with TensorFlow and Keras, it applies data preprocessing and augmentation for high accuracy. Includes model evaluation metrics and an optional Django/Flask web app for real-time image-based predictions.

Brain Tumor Classification using CNN (Deep Learning)
This project focuses on developing a Brain Tumor Classification System using Convolutional Neural Networks (CNN) to automatically detect and classify brain MRI scans as Tumor or No Tumor. The primary goal is to assist radiologists and medical professionals by providing a reliable and AI-driven diagnostic tool for early and accurate tumor detection.

Project Overview
The model is built using TensorFlow and Keras to classify MRI brain images based on the presence of tumors. Data preprocessing, augmentation, and normalization techniques are applied to improve model accuracy and generalization. A CNN architecture is designed with multiple convolutional, pooling, and dense layers to extract image features effectively. The system is evaluated using accuracy, confusion matrix, precision, recall, and F1-score metrics.
Additionally, a simple Flask or Django-based web interface is integrated to allow users to upload MRI images and obtain classification results in real time.

Tech Stack
Languages: Python
Frameworks & Libraries: TensorFlow, Keras, NumPy, OpenCV, Matplotlib, Scikit-learn
Web (Optional): Flask / Django
Dataset: Brain Tumor MRI Dataset – Kaggle

Model Performance
The model achieved an accuracy of approximately 97% after implementing data augmentation and hyperparameter tuning. The loss decreased significantly through the use of batch normalization and dropout layers, ensuring better generalization and reduced overfitting.

Key Features
1.MRI image upload and automatic classification (Tumor / No Tumor)
2.Visualization of model performance during training (loss vs. accuracy)
3.Explainable predictions using Grad-CAM for model interpretability
4.Trained model saved and loaded using the .h5 format

Conclusion
This project demonstrates the potential of deep learning in medical image analysis by automating tumor detection from MRI scans. It provides a foundation for future enhancements such as multi-class tumor classification, real-time deployment, and integration into clinical diagnostic workflows.
