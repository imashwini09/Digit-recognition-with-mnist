
# Handwritten Digit Recognition with MNIST Dataset

This project is a Python-based application that uses a machine learning model to recognize handwritten digits. It utilizes the popular MNIST dataset and provides a graphical interface using Tkinter to allow users to draw digits and receive predictions in real-time.

## Features

- **Handwritten Digit Recognition**: The application uses a pre-trained neural network to classify handwritten digits (0-9).
- **Tkinter GUI**: The user-friendly graphical interface allows users to draw digits, clear the canvas, and get predictions instantly.
- **MNIST Dataset**: The model is trained on the MNIST dataset, a well-known dataset for digit recognition tasks.

## Installation

### Prerequisites

Before you can run this project, ensure you have the following installed:

- Python 3.11+

# SETUP
```
python -r requirements.txt
```
Run python file to get model
```
python Cnn_digit_recognition.py
```
If Fine-tuning needed you can use Cnn_digit_recognition.ipynb file for more layers and epochs.
Hyper-parameter can be tuned.

Download the model store in same directory
Run Tkinter gui file to test
```
python gui_digit_recognizer.py
```
## Usage
Draw a digit (0-9) in the provided canvas.
Click the Predict button to get the recognized digit.
The application will display the predicted digit in the output box.
Use the Clear button to reset the canvas and draw again.

## Files
gui_digit_recognizer.py: The main Tkinter GUI application file.
Cnn_digit_recognition.py: The neural network model file (training and prediction logic).
README.md: Project documentation.

## Model Architecture
The model used for digit recognition is a Convolutional Neural Network (CNN) trained on the MNIST dataset. The architecture consists of the following layers:

Conv2D layers with ReLU activation
MaxPooling2D layers
Flatten layer to convert 2D features to 1D
Dense (fully connected) layers with softmax for classification
## Contributing
Feel free to submit issues or pull requests to contribute to the project.

### Instructions:
- Replace `yourusername` and `your-repo-name` with your GitHub username and repository name.
- Include an actual screenshot of the GUI in the `screenshots` directory (you'll need to create this directory in your project).
- Update file names if necessary, based on your actual project structure.

Let me know if you need further adjustments!
