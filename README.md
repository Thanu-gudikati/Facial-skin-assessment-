Facial Skin Type Classification Using Machine Learning:

Overview:-

This project aims to classify facial skin types (oily, dry, normal) using machine learning models. 
Accurate skin type classification is essential for personalized skincare and dermatological treatments.

Repository Structure:-

The dataset used is uploaded in the repository. All code, including preprocessing, model training, and evaluation, is available in Colab notebook uploaded to the repository.

Approach:-

Data Collection: 
Manually gathered and labeled a dataset of facial images into oily, dry, and normal categories using clustering techniques.

Data Preprocessing: 
Applied image resizing, data augmentation, train-test split (80:20 ratio), and one-hot encoding.

Model Training and Evaluation:
Trained and evaluated multiple machine learning models including SVM, KNN, Decision Tree, 
ResNet50, VGG16, and EfficientNetB0.

Key Results:-

Models Used:

Support Vector Machine: 62.5% accuracy

K-Nearest Neighbors: 75% accuracy

Decision Tree: 37.5% accuracy

ResNet50: 62.5% accuracy

VGG16: 87.5% accuracy

EfficientNetB0: 50% accuracy

Best Performing Model: VGG16 achieved the highest accuracy of 87.5%, making it the most effective model for facial skin type classification in this study.

Conclusion:-

The VGG16 model's superior performance underscores its potential for image classification in skincare and dermatology, highlighting 
the importance of advanced machine learning techniques in the health sector.

Technologies Used:-

Programming Language: Python

Libraries: TensorFlow, Keras, OpenCV, Pandas

Development Environment: Google Colab
