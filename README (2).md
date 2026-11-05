# Artificial Neural Networks: Perceptrons, PyTorch and NumPy from Scratch

Three steps toward understanding neural networks: **hand-designed perceptrons**, a **2-layer network in PyTorch**, and the same **2-layer network built from scratch in NumPy**, with forward pass and backpropagation written by hand.

## 🎯 What this project does

### 1. Seven-segment display classifier
- Represents the digits 0–9 as 7-dimensional binary vectors, one value per display segment
- **Hand-designs 10 perceptrons** with chosen weights and biases, which classify all 10 digits correctly
- Trains the same single-layer network with **PyTorch** (`nn.Linear`, MSE loss, SGD) and compares the learned weights with the hand-designed ones

### 2. MNIST digit classification with PyTorch
- 2-layer network: `784 → 32 (ReLU) → 10`
- Splits the training data 80/20 into training and validation sets
- Saves the best model by validation loss
- Plots training and validation loss

### 3. The same network from scratch with NumPy
- Forward pass, squared-error loss and **manual backpropagation** (gradients for both weight matrices)
- Stochastic gradient descent, with no deep learning library

## 📊 Results
| Model | Test accuracy (MNIST) |
|-------|----------------------:|
| 2-layer network, PyTorch | **90.87%** |
| 2-layer network, NumPy from scratch | **87.02%** |

## 🛠️ Tech Stack
Python · PyTorch · torchvision · NumPy · Matplotlib · Jupyter

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook ann_from_scratch.ipynb
```
The MNIST dataset downloads automatically the first time you run the notebook.

## 👤 Author
Masooma, MSc Applied AI, Year 1
