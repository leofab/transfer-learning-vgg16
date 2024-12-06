# Image Classifier with Pretrained VGG16

This project implements an image classification pipeline using the VGG16 convolutional neural network pretrained on ImageNet. The classifier is fine-tuned to classify images from a custom dataset.


## Features

- Preprocessing: Images are resized to 224x224, normalized, and processed using VGG16's preprocessing pipeline.
- Dataset Handling: The dataset is divided into training, validation, and test sets.
- Model Customization: The original VGG16 top layers are replaced with a custom softmax classification layer for fine-tuning on the target dataset.
- Training and Evaluation: Includes functionality to train and evaluate the model, track performance metrics, and visualize sample images.


## Dependencies

- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib


## Usage

1. Clone the repository and navigate to the project directory.
2. Prepare your dataset in the specified folder structure.
3. Run the scripts to preprocess data, train the model, and evaluate its performance.
