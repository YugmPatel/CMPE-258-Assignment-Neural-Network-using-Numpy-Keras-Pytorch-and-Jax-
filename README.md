# 3-Layer Neural Network for Non-linear Regression – Multi-Framework Assignment

This repository contains multiple implementations of a **3-layer neural network** for **non-linear regression** using a synthetic 3-variable equation. Each implementation satisfies specific constraints such as using TensorFlow's `einsum`, manual backpropagation, and different levels of abstraction in various frameworks.

## 📌 Overview
- ✅ Synthetic dataset using 3-variable non-linear function  
- ✅ 3-layer neural network in all implementations  
- ✅ Manual backpropagation (NumPy & PyTorch low-level)  
- ✅ TensorFlow `einsum` used instead of matmul  
- ✅ 4D and 2D slice visualizations  
- ✅ Public GitHub repo with clean documentation  
- ✅ Video walkthroughs included and linked  

## 🧪 Dataset Description
The synthetic dataset is generated using the following non-linear equation:
- 100 samples  
- 3 input features (x1, x2, x3)  
- Gaussian noise added for realism  

## 📊 Visualization
- **4D Plot** – 3 input features on X, Y, Z axes and predicted `y` as color  
- **2D Slices** – Fix one input variable and vary the other two  
- **Training Loss Curves** – Monitor training performance over epochs  

## 🔍 Implementations
| Label | Framework | Description |
|-------|-----------|-------------|
| `a`   | NumPy      | From-scratch manual NN with backpropagation and chain rule |
| `b`   | PyTorch (manual) | No `nn.Module`; manual layers and gradient computation |
| `c`   | PyTorch (`nn.Module`) | Built-in modules and autograd |
| `d`   | PyTorch Lightning | Cleaner modular implementation using Lightning |
| `e1`  | TensorFlow (low-level) | Manual layer setup using `einsum`, custom training loop |
| `e2`  | TensorFlow (built-in layers) | Keras Sequential API with custom training loop |
| `e3`  | TensorFlow (Functional API) | Functional API for flexible architecture |
| `e4`  | TensorFlow (High-Level API) | Fully-managed model using Keras API |

## 🎥 Video Walkthroughs
Each implementation includes a recorded video walkthrough that covers:
- GitHub check-in verification  
- Step-by-step code explanation  
- Training and output analysis  
- Colab execution and visualizations  

📺 **[Watch the Complete Video on YouTube](https://youtu.be/EEhzYPAKo2w)**

The video includes detailed explanations of:
- Dataset generation and preprocessing
- Neural network architecture and implementation details
- Manual backpropagation vs. autograd approaches
- Visualization techniques for 3D and 4D data
- Performance comparisons between frameworks
- Best practices for each implementation approach

## ✅ Notes
- All notebooks are cleaned and fully commented  
- Manual backpropagation implemented in NumPy & PyTorch low-level versions  
- TensorFlow version strictly uses `einsum` for matrix operations as required  
- Public access is granted for all files and links
