# MobileViT-Based Edge AI Optimization for Visual Wake Words

A lightweight computer vision project focused on efficient binary image classification using **MobileViT**, with post-training INT8 quantization and ONNX export for edge AI deployment.

## 📌 Project Overview

This project explores the optimization of a MobileViT-based deep learning model for the **Visual Wake Words (VWW)** dataset. The objective is to achieve a balance between classification accuracy, model size, memory efficiency, and inference deployment requirements for resource-constrained edge devices.

The model is trained using PyTorch and evaluated in both FP32 and INT8 precision to assess the impact of post-training quantization on predictive performance and model compression.

## 🎯 Objectives

- Develop a lightweight MobileViT-based model for binary image classification.
- Optimize model size using post-training INT8 quantization.
- Compare FP32 and INT8 model accuracy.
- Evaluate classification performance using standard metrics and a confusion matrix.
- Export the optimized model to ONNX for cross-platform inference and edge deployment.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Model Architecture:** MobileViT
- **Domain:** Computer Vision
- **Model Optimization:** INT8 Post-Training Quantization
- **Model Interoperability:** ONNX
- **Evaluation:** Accuracy, Precision, Recall, F1-score, Confusion Matrix, Training-Loss Analysis
- **Application Area:** Edge AI and Resource-Constrained Inference

## 📊 Results and Performance

The optimized model was evaluated to understand the trade-off between model size and classification accuracy.

| Metric | FP32 Model | INT8 Model |
|---|---:|---:|
| Classification Accuracy | 95.10% | 95.15% |
| Model Size | 3.92 MB | 2.47 MB |
| Model Size Reduction | — | ~37% |

### Key Findings

- Achieved **95.10% accuracy** with the original FP32 model.
- Achieved **95.15% accuracy** after INT8 post-training quantization.
- Reduced model size from **3.92 MB to 2.47 MB**, representing approximately **37% compression**.
- Evaluated classification performance using precision, recall, F1-score, and confusion matrix analysis.
- Exported the model to ONNX to support cross-platform inference workflows.

The results indicate that INT8 quantization substantially reduced model size while maintaining comparable classification accuracy.

## ⚙️ Methodology

### 1. Dataset and Preprocessing
Used the Visual Wake Words (VWW) dataset for binary image classification. The data was prepared for model training and evaluation using the preprocessing pipeline implemented in the project notebook.

### 2. Model Development
Developed a lightweight MobileViT-based computer vision model using PyTorch for the VWW classification task.

### 3. Model Evaluation
Evaluated the FP32 model using classification accuracy, precision, recall, F1-score, confusion matrix analysis, and training-loss trends.

### 4. INT8 Quantization
Applied post-training INT8 quantization to reduce the model's storage footprint and improve its suitability for resource-constrained deployment.

### 5. ONNX Export
Exported the trained model to ONNX format to support interoperable inference and potential deployment across compatible edge inference runtimes.

## 🚀 Getting Started

### Prerequisites

- Python
- PyTorch
- Jupyter Notebook
- ONNX and the relevant ONNX export or inference dependencies

The exact dependency versions and additional packages should match those used in the original notebook.

### Run the Project

1. Open the original Kaggle notebook linked below.
2. Review the dataset configuration and preprocessing steps.
3. Set up the required Python environment.
4. Download or configure access to the Visual Wake Words dataset as described in the notebook.
5. Run the notebook cells in sequence to reproduce the training, evaluation, quantization, and ONNX export workflow.

**Note:** Dataset files and trained model artifacts are not included in this repository by default. Follow the notebook's dataset and artifact configuration to obtain them.

## 🔗 Project Resources

- **Original Kaggle Notebook:** [MobileViT-Based Edge AI Optimization for Visual Wake Words](https://www.kaggle.com/code/akhilajanagam/notebook5c4af34f5b)
- **Dataset:** Visual Wake Words (VWW) dataset — access and download instructions should follow the original notebook's configuration.

## 💡 Applications

- Always-on visual recognition on edge devices
- Lightweight image classification
- Resource-efficient computer vision inference
- Edge AI prototyping for embedded and low-memory environments

## 👩‍💻 Author

**Janagam Akhila**

- GitHub: [akhilajanagam799](https://github.com/akhilajanagam799)
- LinkedIn: [Janagam Akhila](https://linkedin.com/in/janagam-akhila-297b65307)

---

*This project demonstrates the application of model compression and deployment-oriented optimization techniques to lightweight computer vision models for edge AI.*

