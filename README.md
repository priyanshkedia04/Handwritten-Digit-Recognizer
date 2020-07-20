# Handwritten-Digit-Recognizer
This code helps you classify Handwritten Numbers using Convnets with an accuracy above 99%

Handwritten Number Dataset from Kaggle was used to train the model. It was further used to develop a program to recognize Handwritten Numbers on paper and is totally suitable for real-life examples. Dataset had a total of 70,000 (28x28 px) images and 10 Labels (0-9) out of which 60,000 were used for training and rest was divided equally in Validation and Test Dataset.

Keras API with Tensorflow in the backend was used to build the Deep Neural Network. OpenCV was used to detect multiple digits in a single image using Contours.
Model Architecture:
Conv2D=>MaxPool2D=>Conv2D=>Conv2D=>MaxPool2D=>Dense=>Dense

Training Accuracy: 99.97%

Validation Accuracy: 99.28%

Test Accuracy: 99.30%
## Getting Started

### Dependencies

* Jupyter Notebook required

* Python Libraries

    - Imutils
    - Tensorflow
    - Keras
    - Numpy
    - cv2
    - os
    - Scikit-Learn
    - Matplotlib

### Installing

* Download Jupyter Notebook

* No further installation


### Executing program

There are 4 phases of this program, run each of them.

* Train a Deep Convolutional Neural Network to recognize numbers 0-9 using the Handwritten Number Dataset

* Detect and localize multiple numbers in the in the Binary Threshold image using Contours Detection method of OpenCV 
* Classify the selected Contours using the Trained DCNN model

## Help

Installing the libraries beforehand will solve most issues

## Authors

Contributors names and contact info 
ex. [@priyanshkedia04](https://github.com/priyanshkedia04)

## Version History

* 0.1
    * Initial Release

## License

GNU General Public License v3.0
