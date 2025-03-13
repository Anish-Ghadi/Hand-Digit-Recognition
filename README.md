# Digit Recognition using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow to recognize handwritten digits.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Testing and Evaluation](#testing-and-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

Ensure you have Python installed (recommended version: 3.8+). Then, install the required dependencies:

```sh
pip install tensorflow numpy pandas matplotlib seaborn
```

## Dataset

This project uses the MNIST dataset, a collection of handwritten digits from 0 to 9. The dataset is loaded directly from TensorFlow's datasets module.

## Usage

Run the Jupyter Notebook to execute the code step by step:

```sh
jupyter notebook digit_recognition_cnn.ipynb
```

## Training the Model

The CNN model is defined using TensorFlow/Keras and trained using the MNIST dataset. The training process includes:
- Data preprocessing (normalization and reshaping)
- Defining the CNN architecture
- Compiling the model with loss and optimizer
- Model training with batch processing

## Testing and Evaluation

Once trained, the model is evaluated on test data to determine accuracy and performance.

To test the model, you can use:
```python
test_loss, test_acc = model.evaluate(X_test, y_test, verbose=2)
print("Test accuracy:", test_acc)
```

## Results

The trained model achieves high accuracy on the MNIST dataset, effectively recognizing handwritten digits.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements.

## Contact

https://github.com/Anish-Ghadi | anishghadi001@gmail.com

