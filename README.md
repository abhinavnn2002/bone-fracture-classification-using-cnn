# bone-fracture-classification-using-cnn
This project aims to develop a deep learning-based system to classify bone fractures from X-ray images into two categories: fractured and non-fractured.
By automating the process of identifying fractures, this project seeks to support radiologists and medical practitioners, reducing diagnostic time and improving accuracy in clinical settings.

## Objective
The primary objective of this project is to create an efficient and accurate model capable of distinguishing between fractured and non-fractured bones using computer vision techniques.
This can serve as a foundational tool in medical imaging for assisting doctors in analyzing radiographs.

## Dataset
The dataset used for this project was picked from picked from kaggle ("https://www.kaggle.com/datasets/bmadushanirodrigo/fracture-multi-region-x-ray-data") consists of X-ray images of fractured and non-fractured bones, obtained from an open-source platform such as Kaggle. 
The data is divided into training, validation, and testing subsets. The images are preprocessed and labeled to ensure consistency and quality during model training.
The dataset includes multiple image formats and resolutions, which were standardized during preprocessing.

## Model architecture
The model is built using a Convolutional Neural Network (CNN) architecture designed for binary classification. The architecture consists of four convolutional layers for extracting spatial and texture features, followed by Batch Normalization to stabilize and speed up the training process. MaxPooling layers are used for down-sampling, and a Global Average Pooling layer is employed to reduce the dimensions while retaining essential features. 
Fully connected layers with Dropout are added to prevent overfitting, and the final Dense layer with a sigmoid activation function outputs the classification result.

## Fututre work
This project has the potential for significant expansion. Future improvements could include using a larger and more diverse dataset, implementing multi-class classification to identify specific types of fractures, and applying transfer learning with pre-trained models like ResNet or EfficientNet.
Moreover, integrating the model into a web or mobile application could make it a practical tool for real-time use in hospitals and clinics.
