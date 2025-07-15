# CodeAlpha Handwritten Character Recognition

## Project Description
This project builds a CNN model to recognize handwritten digits (0–9) using the MNIST dataset.

## Dataset
- **MNIST** dataset (60,000 training + 10,000 test images)
- Grayscale, 28x28 pixel images

## Model Architecture
- Conv2D → MaxPooling
- Conv2D → MaxPooling
- Flatten → Dense (128) → Output (10 classes)

## Accuracy
- Achieved ~98% accuracy on test data

## Tools Used
- Python
- TensorFlow / Keras
- Matplotlib, NumPy

## Output Sample
The model was able to correctly classify test images like the ones below:

<img width="1163" height="277" alt="image" src="https://github.com/user-attachments/assets/15561ed6-9e83-45a3-a872-6680394ffd6d" />


## How to Run
1. Clone the repository
2. Open notebook in Jupyter or Colab
3. Run cells in order to train and test the model
