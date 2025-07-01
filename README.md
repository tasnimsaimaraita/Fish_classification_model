# Fish Image Classification

This repository contains a project on fish species image classification using deep learning techniques. The complete code is implemented in a Jupyter notebook available [here](https://github.com/fragliglint/Fish_Classification/blob/main/fish.ipynb).


Dataset: https://data.mendeley.com/datasets/8r24222wcc/2

## Project Description

This project performs image classification on a fish dataset, involving:

- **Dataset splitting:**  
  The original fish images are organized into class subfolders and split into training (70%), validation (15%), and testing (15%) sets.

- **Modeling:**  
  Two models are implemented and compared:
  - **Artificial Neural Network (ANN):** A fully connected neural network that flattens input images and achieves approximately **49.37%** accuracy on the test set.
  - **Convolutional Neural Network (CNN):** A convolutional model with multiple convolutional and pooling layers that achieves approximately **90.08%** accuracy on the test set.

- **Evaluation:**  
  Both models are trained and evaluated using TensorFlow Keras API, employing categorical cross-entropy loss and accuracy metrics.

- **Visualization:**  
  To validate the CNN model’s predictions visually, 10 random test images are displayed alongside their true labels and predicted labels.



## Repository Structure

- `fish.ipynb` — Jupyter notebook containing the full code for dataset splitting, model training, evaluation, and visualization.
- Dataset folders (not included in repo):  
  - Original dataset folder structure:  

    Fish Data/
      ├── class_1/
      ├── class_2/
      └── ...
   
  - Split dataset structure created by the code:  
  
    Fish Data Split/
      ├── train/
      ├── val/
      └── test/
  



## How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/fragliglint/Fish_Classification.git
   cd Fish_Classification
