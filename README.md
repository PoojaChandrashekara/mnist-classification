Markdown
# MNIST Digit Classification with Neural Network

This project implements a neural network to classify handwritten digits from the MNIST dataset. It demonstrates building, training, and evaluating a multi-layer perceptron (MLP) model using Keras.

## Project Structure

- `README.md`: This file provides general information about the project.
- `mnist_classification.py`: Contains the Python code for building and training the model.
- `requirements.txt`: Lists the required Python libraries.
- (Optional) `data`: Directory to store the MNIST dataset (if not downloaded automatically).
- (Optional) `models`: Directory to store saved model weights.

## Usage

1. Install the required libraries:
   ```bash
   pip install -r requirements.txt

2. Run the Python script:
   ```bash
   python mnist_classification.py
3. Key Features
      Loads and preprocesses the MNIST dataset.
      Builds a neural network with 3 hidden layers and a softmax output layer.
      Compiles the model with the Nadam optimizer and categorical crossentropy loss.
      Trains the model for 10 epochs with a batch size of 1024.
      Evaluates the model's performance on the test set.
      Makes predictions on individual test images.

4. Results
The model achieves an accuracy of approximately 95% on the test set.
