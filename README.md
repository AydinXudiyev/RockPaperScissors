# Rock-Paper-Scissors Image Classification

This project is a machine learning application that uses a Convolutional Neural Network (CNN) to classify images of the gestures in the game "Rock-Paper-Scissors." By training a model on labeled images of these three gestures, the project demonstrates how deep learning can be used to identify basic hand signs.

## Project Goals

The main goal is to build a model that can distinguish between images of a hand showing "rock," "paper," or "scissors." This type of image classification project highlights the steps needed to preprocess image data, train a model, and evaluate its performance.

## Key Steps

1. **Data Preparation**: Images are collected and categorized into three folders for "rock," "paper," and "scissors." They are then preprocessed and resized for input consistency.
2. **Model Design**: A CNN model is created with several convolutional and pooling layers to extract and learn the patterns associated with each gesture.
3. **Training and Testing**: The model is trained on the dataset with a portion reserved for validation, allowing us to observe its ability to generalize to unseen images.
4. **Prediction**: Once trained, the model can be used to classify new images, predicting whether a hand in an image is showing rock, paper, or scissors.

## Applications

This image classification approach can be expanded to recognize other types of gestures or objects, making it a foundation for more complex computer vision projects. It could be useful in areas like educational apps, interactive games, or gesture-controlled systems.

## Requirements

- Python 3.x
- TensorFlow
- Supporting libraries like NumPy and Matplotlib for data handling and visualization

## Conclusion

This project demonstrates how to build an image classification model from scratch, using a CNN to recognize simple hand gestures with high accuracy. It provides a useful example of how deep learning can be applied to image-based problems and adapted for real-world applications in gesture recognition.
