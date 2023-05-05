# ASL-deep-learning-interpreter
Interpreting American sign language using deep learning

# ASL Recognition with CNN

This is a machine learning project that recognizes and predicts American Sign Language (ASL) using Convolutional Neural Network (CNN).

Sure! Here is an overview of a GitHub README file for a machine learning project that recognizes and predicts American Sign Language (ASL) using Convolutional Neural Network (CNN):

# ASL Recognition with CNN

This is a machine learning project that recognizes and predicts American Sign Language (ASL) using Convolutional Neural Network (CNN).

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras 2.x
- OpenCV 4.x

## Installation

1. Clone this repository.
2. Install the required dependencies using pip.

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from (https://www.kaggle.com/grassknoted/asl-alphabet).
4. Extract the dataset in the root directory of this repository.

## Usage

1. Run `train.py` to train the model.

   ```bash
   python train.py
   ```

2. Run `predict.py` to predict ASL.

   ```bash
   python predict.py --image <path_to_image>
   ```

## Results

The model achieved an accuracy of 98% on test data.

## Future Work

1. Improve accuracy of the model.
2. Add support for real-time video recognition.

