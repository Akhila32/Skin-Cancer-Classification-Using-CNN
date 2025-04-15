#  Skin Cancer Classification Using CNN

##  Introduction
Skin cancer is one of the most common forms of cancer worldwide. Early detection plays a crucial role in increasing survival rates and improving treatment effectiveness.  
This project leverages **Convolutional Neural Networks (CNNs)** to build a deep learning-based system that classifies skin conditions and assists in early diagnosis.

---

##  Dataset
The project uses the **International Skin Imaging Collaboration (ISIC)** dataset, which contains labeled images of different skin conditions.  
Key classes include:

- **Melanoma**  
- **Dermatofibroma**  
- **Nevus Pigmentosus**  
- **Squamous Cell Carcinoma**  
- **Healthy Skin**

---

##  Technologies Used
- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow / Keras  
- **Computer Vision:** OpenCV  
- **Data Processing & Visualization:** Pandas, NumPy, Matplotlib  

---

##  Model Architecture
The CNN model is designed to extract spatial features from skin lesion images. The architecture includes:

- **Convolutional Layers:** To capture local patterns and textures  
- **Pooling Layers:** To reduce dimensionality and computation  
- **Fully Connected Layers:** For classification  
- **Activation Functions:**  
  - `ReLU` for non-linearity  
  - `Softmax` for multi-class classification  

---

##  Implementation Steps

### 1. Data Preprocessing
- Image resizing and normalization  
- Data augmentation to enhance generalization  

### 2. Building the CNN Model
- Layers constructed using TensorFlow/Keras  
- Dropout layers added to reduce overfitting  

---

##  Model Training & Evaluation
- Training the model with labeled skin lesion images  
- Evaluating model performance using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**

---

##  Results & Performance

The trained model achieved **training accuracy between 90% and 94%**, showing its capability in classifying different types of skin lesions effectively.  
The **Adam optimizer** and CNN-based feature extraction contributed to the high accuracy and reliable performance of the system.

Below is the confusion matrix showing classification performance:

![Confusion Matrix](confusion_matrix.PNG)

The matrix reveals strong classification across all categories, with very few misclassifications.


