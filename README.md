# Workshop Projects – Deep Learning

This repository contains two deep learning projects implemented using Python and Google Colab as part of a technical workshop.

## 1. Artificial Neural Network (ANN) Implementation

### Project Description
An Artificial Neural Network (ANN) is a deep learning model inspired by the structure of the human brain. It consists of interconnected neurons organized into input, hidden, and output layers. The network learns patterns from training data by adjusting weights and biases.

### Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Google Colab

### Implementation Steps
1. Import the required Python libraries.
2. Load the dataset and examine its structure.
3. Preprocess the data by handling missing values and encoding categorical variables, if required.
4. Split the dataset into training and testing sets.
5. Normalize or scale the input features, if required.
6. Build the ANN model using an input layer, hidden layers, and an output layer.
7. Compile the model using an appropriate optimizer, loss function, and evaluation metric.
8. Train the model using the training dataset.
9. Evaluate the trained model using the testing dataset.
10. Visualize the training performance and analyze the predictions.

### Expected Outcome
The ANN learns patterns from the training data and uses them to make predictions on unseen data. Its performance can be evaluated using suitable metrics based on the task.

---

## 2. Dog and Cat Image Classification Using CNN

### Project Description
This project uses a Convolutional Neural Network (CNN) to classify images into two categories: dogs and cats. CNNs are deep learning models designed to automatically extract visual features such as edges, shapes, textures, and patterns from images.

### Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab
- Convolutional Neural Network (CNN)

### Implementation Steps
1. Import the required libraries.
2. Load the dog-and-cat image dataset.
3. Preprocess the images by resizing them to a fixed dimension and normalizing pixel values.
4. Divide the dataset into training and validation sets.
5. Construct a CNN using three convolutional layers.
6. Apply activation functions and pooling layers to extract important image features.
7. Flatten the extracted features and pass them through fully connected layers.
8. Add a suitable output layer for binary classification.
9. Compile the model using an appropriate optimizer and loss function.
10. Train the model using the training images.
11. Evaluate the model using validation data.
12. Test the trained model on sample images and display the predicted class.

### Expected Outcome
The trained CNN predicts whether an input image contains a dog or a cat. Model performance can be analyzed using accuracy, loss curves, and predictions on sample images.

---

## How to Run the Projects

1. Open the corresponding Google Colab notebook.
2. Run the cells in sequential order.
3. Ensure the required dataset is available and the dataset paths are correctly configured.
4. Train the model and evaluate its performance.
5. Test the model using sample inputs.

## Conclusion

These projects demonstrate the practical implementation of deep learning techniques using Python. The ANN project introduces neural network training for structured data, while the CNN project demonstrates image classification using convolutional layers.

Both projects provide practical experience in dataset preparation, model development, training, evaluation, and prediction.
