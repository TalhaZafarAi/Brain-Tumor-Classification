
# Brain Tumor Classification

Brain Tumor Classification is a project that leverages powerful Python libraries like Keras and OpenCV to create a Brain Tumor Classification system. The system is trained with a InceptionV3 is a deep convolutional neural network and provides robust functionality for detecting brain tumors from medical images.

InceptionV3 is a deep convolutional neural network architecture developed by Google, known for its efficiency and high performance in image classification tasks. It builds on the Inception family, featuring improvements such as factorized convolutions, regularization, and efficient grid size reduction. The network consists of symmetric and asymmetric building blocks, including convolutions, average pooling, max pooling, dropouts, and fully connected layers. These blocks enable the network to capture intricate patterns and features at multiple scales. The "include_top=False" parameter excludes the top fully connected layers, allowing the model to be customized for new tasks. This pre-trained model, trained on ImageNet, provides robust feature extraction, making it a popular choice for transfer learning in various computer vision applications.

## Features

- Utilizes Keras and OpenCV for image processing and model training.
- Trained with a InceptionV3 is a deep convolutional neural network for high accuracy.
- Visualizes image samples and class distribution.
- Splits data into training and testing sets.
- Predicts and evaluates model performance.

## Requirements

- Python 3
- Keras
- OpenCV
- Matplotlib
- Seaborn
- scikit-learn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/brain-tumor-classification.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python main.py
   ```

## Usage

1. Load the dataset from your Google Drive.

2. Set the path to the dataset folder in your Google Drive.

3. Read images from the 'no' and 'yes' folders.

4. Display sample images from both classes.

5. Visualize class label distribution.

6. Define class labels and preprocess images.

7. Split the data into training and testing sets.

8. Implement the model.

9. Train and evaluate the model.

10. Predict class labels for test images.

11. Plot the confusion matrix.

12. Plot model loss and accuracy.

## Acknowledgements

This project was developed with the help of the following resources:

- [Keras](https://keras.io/)
- [OpenCV](https://opencv.org/)
- [Google Colab](https://colab.research.google.com/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)

---

Feel free to contribute to this project by opening issues or submitting pull requests on GitHub. For any questions or support, please contact me directly.
