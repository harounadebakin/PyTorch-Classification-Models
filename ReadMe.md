# PyTorch Model Projects

This repository contains multiple Jupyter Notebooks demonstrating deep learning workflows using PyTorch. The projects focus on building and training classification models, including binary and multiclass classification, as well as replicating a CNN architecture (TinyVGG) using Torchvision.

## Project Overview

### 1. Binary Classification Model with PyTorch
This notebook walks through creating a binary classifier using PyTorch. Key steps include:
- Data preparation and loading with `DataLoader`
- Defining a neural network model
- Training loop with loss and accuracy tracking
- Model evaluation and inference

### 2. Multiclass Classification Model with PyTorch
This notebook expands to multiclass problems, demonstrating:
- Handling multiple categories in datasets
- One-hot encoding and CrossEntropyLoss
- Metrics for multiclass accuracy
- Visualization of predictions

### 3. Torchvision and Replicating TinyVGG
This notebook replicates the TinyVGG architecture using Torchvision, covering:
- Implementing TinyVGG-like CNN
- Using `torchvision.transforms` for image preprocessing
- Training on image datasets
- Comparing model performance

## Repository Structure
```
├── Binary_Classification_Model_With_PyTorch.ipynb
├── Multiclass_Classification_Model_With_PyTorch.ipynb
├── Torchvision_and_Replicating_a_CNN_(TINYVGG).ipynb
└── README.md
```

## Requirements
- Python 3.x
- PyTorch
- Torchvision
- Matplotlib
- NumPy

Install dependencies:
```bash
pip install torch torchvision matplotlib numpy
```

## How to Use
1. Open the notebook in Jupyter or VS Code.
2. Run cells sequentially.
3. Modify hyperparameters to experiment with model performance.

## Goals of These Notebooks
- Understand model architecture design in PyTorch
- Learn how to train and evaluate models
- Explore image classification with CNNs

## Future Improvements
- Add training with GPU support
- Integrate TensorBoard for visualization
- Save and load models using `torch.save`

---
Feel free to contribute or adapt these notebooks for your own deep learning experiments!

