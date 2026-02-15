# DeepVision: CNN Architectures & Transfer Learning Analysis

This project explores the field of Computer Vision through the implementation and evaluation of various Deep Learning architectures. It focuses on the comparison between training Convolutional Neural Networks (CNNs) from scratch and utilizing Transfer Learning with state-of-the-art architectures.

## 🎯 Overview
The primary goal of this study is to classify image datasets using different deep learning strategies. The repository covers the entire pipeline, from data preprocessing and augmentation to model evaluation and architectural benchmarking.

## 🚀 Key Features
* **Custom CNN Implementation:** Building and training a Convolutional Neural Network from scratch to understand fundamental feature extraction.
* **Transfer Learning Integration:** Leveraging pre-trained models including **ResNet18** and **MobileNet** for optimized image classification.
* **Performance Benchmarking:** Comparative analysis between training from scratch vs. fine-tuning pre-trained weights.
* **Hyperparameter Optimization:** Evaluation of learning rates, batch sizes, and architectural depth on model convergence.

## 📊 Technical Insights
Based on the experimental results within the project:
* **Efficiency of Transfer Learning:** Pre-trained models significantly reduce training time and resource consumption while providing higher initial accuracy.
* **Model Selection:** **MobileNet** was identified as a highly suitable architecture for smaller datasets due to its lower parameter count and better generalization compared to deeper models like ResNet18.
* **Generalization vs. Control:** While training from scratch offers full architectural control, Transfer Learning proves superior for rapid deployment and limited GPU environments.

## 🛠️ Installation & Usage

### Prerequisites
Ensure you have Python 3.x and the following Deep Learning libraries installed:
```bash
pip install torch torchvision numpy matplotlib seaborn pillow
