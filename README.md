# Pixel-Coordinate-Prediction

This project uses deep learning techniques to predict the coordinates (x, y) of a pixel with a value of 255 in a given 50x50 pixel grayscale image, where all other pixels are 0. The dataset is synthetically generated, with the pixel of interest randomly assigned in each image.

### Table of Contents
1. Installation
2. Project Structure
3. Dataset Generation
4. Model Architecture
5. Training and Evaluation
6. Results
7. Dependencies

### Installation
To install the required dependencies, use the following command:
pip install -r requirements.txt

### Project Structure
├── dataset
│   ├── train
│   │   ├── images
│   │   └── labels
│   └── test
│       ├── images
│       └── labels
├── requirements.txt
├── README.md
└── PixelCoordinatePrediction.ipynb

### Dataset Generation
The dataset consists of 50x50 pixel grayscale images where a single pixel has a value of 255 and all other pixels are 0. The pixel with a value of 255 is randomly placed in the image.

### Model Architecture
The model is a simple Convolutional Neural Network (CNN) with the following layers:
Conv2D
MaxPooling2D
Flatten
Dense
Dropout

The model architecture is defined in the PixelPredictorModel class.

### Training and Evaluation
The model is trained using the generated dataset. The training and validation loss are plotted to evaluate the model's performance.

### Results
The predicted and ground truth coordinates are displayed, and the model's performance is visualized through various plots.
![image](https://github.com/user-attachments/assets/6e51647e-07db-4cc9-b10f-75a3c3e9e86f)

### Dependencies
The project dependencies are listed in the requirements.txt file
