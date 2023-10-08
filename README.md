# PRODIGY_ML_03
# Cat vs. Dog Image Classification with SVM

Welcome to the Cat vs. Dog Image Classification project repository! In this project, I developed a robust image classification model using Support Vector Machines (SVM) to distinguish between images of cats and dogs. The goal was to create an accurate binary classifier capable of handling real-world images.

## Project Overview

### Dataset
The dataset used for this project is the well-known Kaggle "Dogs vs. Cats" dataset, which can be accessed [here](https://www.kaggle.com/c/dogs-vs-cats/data). It contains a large number of images of cats and dogs, making it suitable for training a machine learning model to differentiate between the two.

### Model Architecture
I employed a Support Vector Machine (SVM) for image classification, leveraging its ability to create clear decision boundaries in high-dimensional feature spaces. Here's an overview of the SVM model architecture:

- **Data Preprocessing**: The dataset was preprocessed, including rescaling, data augmentation (e.g., shearing, zooming, and horizontal flipping), and splitting into training and testing sets.

- **Feature Extraction**: Feature extraction techniques, including Histogram of Oriented Gradients (HOG) and color histograms, were used to extract meaningful features from the images.

- **SVM Model**: The SVM model was trained on the feature-rich dataset to learn the patterns that distinguish cats from dogs.

### Model Training
The SVM model was trained with an "hinge" loss function and optimized using the Adam optimizer. The training process involved iterating through 15 epochs, with periodic evaluation on the test set to monitor performance.

## Model Evaluation

The trained model achieved a reasonable accuracy on the test set, as indicated in the training logs. You can further fine-tune the model, experiment with different feature extraction methods, or explore other classification algorithms to improve performance.
