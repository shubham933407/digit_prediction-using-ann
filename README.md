🔢 Digit Recognition with MNIST using ANN
This repository contains a deep learning-based solution for handwritten digit classification using the MNIST dataset. The project leverages an Artificial Neural Network (ANN) built with TensorFlow/Keras to achieve high accuracy in recognizing digits (0–9) from 28x28 grayscale images.
📚 About the Project:
The MNIST dataset is a benchmark in the machine learning community, containing:
60,000 training images
10,000 test images
Each image is a 28x28 grayscale representation of a handwritten digit.

In this project:
ANN is built using Keras Sequential API
Input data is scaled and reshaped for training
The model is trained, validated, and tested
Performance is evaluated using metrics and visualizations

🧠 Model Architecture
A simple feedforward neural network (ANN) with:

🔢 Input Layer: 784 features (28×28 pixels)
🧠 Hidden Layers: Dense layers with ReLU activation
🧮 Output Layer: 10 neurons with softmax activation (for 10 digits)

Loss Function: sparse_categorical_crossentropy
Optimizer: adam
Metrics: accuracy

🧪 Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib / Seaborn
Scikit-learn

📊 Evaluation
Accuracy on training and test datasets
Loss and accuracy plots across epochs
