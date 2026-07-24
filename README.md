# Waste Image Classifier

## Overview
This is a beginner-friendly computer vision project that uses a Convolutional Neural Network to classify waste images into material categories such as cardboard, glass, metal, paper, plastic, and trash.

## Purpose
I created this project to practise image classification, PyTorch, model training, model evaluation, and clear GitHub documentation. The project explores how computer vision can support waste sorting and recycling-related applications.

## Skills Used
- Python
- PyTorch
- torchvision
- NumPy
- pandas
- matplotlib
- Pillow
- image preprocessing
- convolutional neural networks
- model training and validation
- test set evaluation
- confusion matrix
- per-class accuracy
- Jupyter Notebook
- GitHub documentation

## Project Workflow
1. Load the image dataset
2. Explore class distribution
3. Display sample images
4. Apply image transformations
5. Create training, validation, and test datasets
6. Build a simple CNN model
7. Train the model
8. Visualise training loss and accuracy
9. Evaluate the model on the test set
10. Display a confusion matrix
11. Discuss results, limitations, and future improvements

## Dataset
The dataset is not included in this public repository due to size and dataset usage restrictions.

To run the notebook, place the waste image dataset in the following folder structure:

```text
data/waste-images/
├── cardboard/
├── glass/
├── metal/
├── paper/
├── plastic/
└── trash/
```

## what I learned

Through this project, I practised creating a beginner computer vision workflow using PyTorch. I learned how to load image data, preprocess images, train a CNN model, evaluate test performance, and explain model limitations clearly.

## Limitations

This project is beginner-friendly and created for learning. Model performance may depend on dataset size, image quality, lighting, background, class imbalance, and number of training epochs.

## AI Assistance Disclosure

AI tools were used to support project planning, code explanation, README structure, and documentation improvement. I reviewed and edited the project to ensure I understand the workflow, code, and results.

## Future Improvements
Use a larger and more diverse dataset
Add data augmentation
Train for more epochs
Compare a custom CNN with transfer learning models
Add a prediction function for single images
Save and reload trained model weights
Build a simple web demo for waste classification
