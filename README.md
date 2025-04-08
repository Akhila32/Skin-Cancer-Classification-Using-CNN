# Skin-Cancer-Classification-Using-CNN
Introduction

Skin cancer is one of the most common forms of cancer worldwide. Early detection plays a crucial role in increasing survival rates and improving treatment effectiveness. This project leverages Convolutional Neural Networks (CNNs) to develop a deep learning-based system that classifies skin conditions and assists in early diagnosis.

Dataset

The project utilizes the International Skin Imaging Collaboration (ISIC) dataset, a widely recognized dataset containing labeled images of different skin conditions. The key classes include:

Melanoma – A serious and potentially deadly form of skin cancer.

Dermatofibroma – A benign skin lesion.

Nevus Pigmentosus – A common mole with pigmentation.

Squamous Cell Carcinoma – A type of non-melanoma skin cancer.

Technologies Used

Programming Language: Python

Deep Learning Framework: TensorFlow / Keras

Computer Vision: OpenCV

Data Processing: Pandas, NumPy, Matplotlib

Model Architecture

The CNN model is designed to extract spatial features from skin lesion images. The architecture includes:

Convolutional Layers – To capture local patterns and textures.

Pooling Layers – To reduce dimensionality and computational complexity.

Fully Connected Layers – To perform classification.

Activation Functions – ReLU for feature extraction and Softmax for multi-class classification.

Implementation Steps

Data Preprocessing

Image resizing and normalization.

Data augmentation to enhance model generalization.

Building the CNN Model

Constructing layers using Keras and TensorFlow.

Using dropout layers to prevent overfitting.

Model Training & Evaluation

Training the model with labeled skin lesion images.

Evaluating accuracy, precision, recall, and F1-score.

Deployment

Saving the trained model.

Deploying the model for real-time predictions.

Results & Performance

The trained model achieved high accuracy in classifying skin conditions, demonstrating its potential for assisting dermatologists in diagnosis. Performance metrics such as precision, recall, and F1-score were used to evaluate the model.
