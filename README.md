# Machine-Learning-CS-584
Final Project

# Machine Learning for Malaria Detection

## Introduction
This project utilizes deep learning models to identify malaria in human blood cells. It contrasts the performance of the SoftMax and Sigmoid activation functions within the ResNet-50 model.

## Dataset
A customized dataset from Kaggle, consisting of 1000 images with an equal split between parasitized and uninfected images, was used for this study.

## Methods
- Convolutional Neural Networks (CNN) were used to process images into array values.
- Residual Neural Networks (ResNet) were leveraged to handle deeper networks for improved performance.
- Transfer learning was employed with ResNet-50 by freezing initial blocks.
- Both SoftMax and Sigmoid activation functions were tested.
- The data was split into training, validation, and test datasets.

## Results
- The Sigmoid activation function within ResNet-50 provided higher accuracy than SoftMax.
- Data augmentation improved model performance.
- ResNet-50 with Sigmoid activation achieved an accuracy of 91.67%.

## Conclusion
The study demonstrates the effectiveness of machine learning models, particularly the use of Sigmoid activation in ResNet-50, for malaria detection.

## References
The project cites various sources which include peer-reviewed articles, online databases, and other relevant research.

For a detailed understanding of the methodologies, experimental setup, and results, please refer to the paper.



