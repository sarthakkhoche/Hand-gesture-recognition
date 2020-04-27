# Hand-gesture-recognition


The project uses feature learning for recognizing hand gestures.

## Dataset
The [Hand Gesture Recognition Database](https://www.kaggle.com/gti-upm/leapgestrecog) can be found at Kaggle. It contains ~20,000 images in various hand poses.
![Dataset][dataset.png]

## Feature Extraction
It uses AlexNet, a CNN which was pretrained on the ImageNet database. The last layer was removed to extract the features, which can be further used for training.

## Model Training
The features can be trained on any classic machine learning model, like KNN, Random Forest, etc.

The best result was found on LinearSVC with an accuracy of 95.67%
