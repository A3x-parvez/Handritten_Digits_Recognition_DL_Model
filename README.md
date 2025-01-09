
# Handwritten Digit Recognition 🤖🚀

This repository contains a Python project that implements a neural network to recognize handwritten digits using the MNIST dataset. The project uses TensorFlow and Keras for building and training the model.

## Project Overview 📑

Handwritten digit recognition is a classic machine learning problem where the goal is to classify images of handwritten digits (0–9). This project utilizes the MNIST dataset, which is a benchmark dataset in machine learning and computer vision.

## Features 🎯

- **Dataset**: Uses the MNIST dataset of 28x28 grayscale images of digits.
- **Model Architecture**: A neural network built using TensorFlow/Keras.
- **Training and Evaluation**: Includes steps for preprocessing, training, and evaluating the model's performance.

## Project Structure </>

- **Dataset Loading**:
  The MNIST dataset is loaded using `keras.datasets.mnist.load_data()`.

- **Model**:
  A neural network is constructed with layers like:
  - `Flatten`: Converts the 2D image data into a 1D array.
  - `Dense`: Fully connected layers for classification.

- **Training**:
  The model is trained using the training dataset `(60000, 28, 28)` with corresponding labels.

- **Evaluation**:
  The test dataset `(10000, 28, 28)` is used to evaluate the model's accuracy.

## How to Use 🛠️

1. **Prerequisites**:
   - Python 3.x
   - TensorFlow (>=2.x)
   - Keras (included with TensorFlow)
   - Jupyter Notebook (for running the `.ipynb` file)

2. **Run the Notebook**:
   - Open the `HandWritten_Digits_prediction.ipynb` file in Jupyter Notebook.
   - Execute the cells step by step to train and evaluate the model.

3. **Results**:
   - The model outputs its accuracy on the test dataset.

## Installation ⚙ 

Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/A3x-parvez/Handritten_Digits_Recognition_DL_Model.git
cd Handwritten_Digit_Recognition
```

Install the required libraries: 

```bash
pip install tensorflow
```

## Results ✅

The model achieves an accuracy of approximately **97.76%** on the test set. (Replace with actual result after evaluation.)

## Acknowledgments ⭐

- The MNIST dataset, a classic dataset in machine learning.
- TensorFlow/Keras for providing an easy-to-use API for building deep learning models.

---
## Contribution 🤝

Contributions are always welcome! Feel free to submit a pull request or report issues.

## Contact me 📞
If you have any questions or feedback, feel free to reach out:

 - GitHub: A3x-parvez 
 - LinkedIn: Rijwanool Karim 
 - Email: rijwanoolkarim143r@gmail.com

## Thank you for visiting my profile.❤️😊 
