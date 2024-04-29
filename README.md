# Machine Learning - CS 584
Analyze SoftMax and Sigmoid activation function in ResNet-50 model for classifying malaria in human blood cells

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

- ## Results
- Implementing the Sigmoid activation function within the ResNet-50 model yielded a higher accuracy compared to the SoftMax activation function.
- The application of data augmentation techniques resulted in enhanced performance of the model.
- Due to the stochastic nature of the training process, the accuracy displayed by the code can vary with each execution. However, it is frequently observed that the ResNet-50 model with Sigmoid activation attains an accuracy in the vicinity of 91.67%.

## Conclusion
The study demonstrates the effectiveness of machine learning models, particularly the use of Sigmoid activation in ResNet-50, for malaria detection.

## References
The project cites various sources which include peer-reviewed articles, online databases, and other relevant research.

For a detailed understanding of the methodologies, experimental setup, and results, please refer to the final report.



