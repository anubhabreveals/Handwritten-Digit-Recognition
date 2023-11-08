# Handwritten Digit Recognition

## Code Overview

This code focuses on building a neural network model for recognizing handwritten digits. The primary goal is to accurately classify and identify handwritten digits (0 to 9) from images using machine learning techniques.

## Key Components

- **Data**: The project uses the MNIST dataset, which consists of 28x28 pixel images of handwritten digits. It includes both training and testing datasets.

- **Model**: A feedforward neural network model is employed for multiclass classification. The model architecture includes input, hidden, and output layers.

- **Training**: The model is trained on a portion of the MNIST dataset (60%) and validated on a cross-validation set (20%).

- **Evaluation**: The model's performance is assessed using various metrics such as accuracy, precision, recall, F1 score, and a confusion matrix. Misclassified samples are visualized for better understanding.


## Usage

To run and replicate this code, follow these steps:

1. Open and run the Jupyter notebook (`multiclass_classification_on_handwritten_digit_data.ipynb`).

2. Ensure you have the necessary libraries and dependencies installed.

3. Adjust hyperparameters, model architecture, and training parameters as needed.

4. Review the visualizations and evaluation results to understand the model's performance.

## Contributions

Contributions and improvements to this project are welcome. Please feel free to submit issues, suggest enhancements, or make pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).
