# Fashion-MNIST Classifier

A neural network that recognises ten clothing categories from 28×28 greyscale images in the Fashion-MNIST dataset.

## Approach
- Normalised pixel values from 0–255 to 0–1
- Model: `Flatten` → `Dense(128, relu)` → `Dense(10, softmax)`
- Trained with the Adam optimiser and sparse categorical cross-entropy for 5 epochs

## Result
- Training accuracy: 89.1%
- Test accuracy: 87.2%

The notebook also repeats the approach on the MNIST handwritten digits dataset with a wider hidden layer.

## Files
- `Computer Vision Basics-FMNIST.ipynb`: the full notebook

## Tech
Python, TensorFlow, Keras, NumPy, Matplotlib
