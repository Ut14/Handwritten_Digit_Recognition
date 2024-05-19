
# Handwritten Digit Recognition with Neural Networks

This project demonstrates the implementation of a neural network for recognizing handwritten digits using TensorFlow and Keras. The neural network is trained on a dataset of images of handwritten digits and their corresponding labels. The project includes visualization of the dataset, construction and training of the neural network model, and predictions on new data.


## Installation

To run this project, you need to have Python installed along with the following packages:

```bash
pip install numpy tensorflow matplotlib
```
    
## Project Overview

Data Loading and Visualization
- The dataset is loaded using the load_data() function.
- The first and last elements of the dataset are printed for verification.
- A sample of 64 images from the dataset is displayed in an 8x8 grid using Matplotlib.
Softmax Function
- A custom softmax function, my_softmax, is defined and tested with a sample array.
Neural Network Model
- A neural network model is created using TensorFlow and Keras.
- The model consists of three layers:
    - An input layer with 400 units (20x20 pixels per image).
    - Two hidden layers with 25 and 15 units respectively, both using ReLU activation.
    - An output layer with 10 units (one for each digit) using linear activation.
- The model is compiled with Sparse Categorical Crossentropy loss function and Adam optimizer.
- The model architecture is summarized.
Training
- The model is trained for 40 epochs on the dataset.
Prediction
- A sample digit from the dataset is displayed.
- The model is used to predict the digit, and the prediction results are printed.


## Files

To run this project, you will need to add the following files

`public_tests.py`

`autils.py`

`lab_utils_softmax.py`

`deeplearning.mplstyle`

`digit_recognition.ipynb`
