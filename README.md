# MNIST Handwritten Digit Recognition

A neural-network project that classifies handwritten digits from the MNIST dataset.

## Project overview
- Dataset: MNIST
- Input: 28 × 28 grayscale digit images
- Classes: Digits 0–9
- Framework: TensorFlow / Keras

## Workflow
1. Load the MNIST training and test datasets.
2. Normalize pixel values to the 0–1 range.
3. Flatten each image and pass it through fully connected Dense layers with ReLU activations.
4. Use a 10-unit softmax output layer for digit classification.
5. Train for 10 epochs, evaluate on test data and compare sample predictions with their true labels.
6. Plot training/validation accuracy and loss.

## Recorded result
**Test accuracy: 97.52%** (from the supplied notebook's recorded evaluation output).

## Run
Open `mnist_digit_recognition.ipynb` in Jupyter or Google Colab and run the cells in order. Keras downloads MNIST on first use.

## Dependencies
See [requirements.txt](requirements.txt).

## Notes
The supplied notebook was reconstructed from a PDF and contains page-transcript material alongside extracted code. Review the cells before relying on it as a clean, fully reproducible notebook.
