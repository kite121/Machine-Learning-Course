# Machine Learning Course

A notebook-based repository with lab assignments and self-practice work from a Machine Learning course. The repository is organized as a compact archive of weekly labs: each notebook focuses on one topic, method, or practical exercise, from ML fundamentals to neural networks, decision trees, and ensemble learning.

## About the course

The course is designed to build both theoretical understanding and practical intuition in machine learning.

### Learning objectives

- develop a sound theoretical and practical understanding of machine learning;
- understand the strengths and weaknesses of popular machine learning approaches;
- see the mathematical relationships across supervised and unsupervised learning methods;
- design and implement the studied algorithms in Python for real-world tasks.

## How the repository is organized

All course work is stored as standalone `Jupyter Notebook` files in the repository root.

- one notebook = one lab or self-practice task;
- file names map directly to weekly topics: `Lab1_...`, `Lab2_...`, ...;
- the repository is course-oriented rather than project-oriented;
- notebooks combine short theory, guided tasks, code, and experiments.

This is not a single end-to-end application. It is a structured collection of practical course materials and exercises.

## Topics covered in this repository

The notebooks currently included in the repository cover the following parts of the course:

| Notebook | Topic |
|---|---|
| `Lab1_Introduction.ipynb` | Introduction to machine learning, supervised learning, regression/classification basics, core concepts |
| `Lab2_Basic_Libraries.ipynb` | ML pipeline overview and core Python libraries: `NumPy`, `Pandas`, `Matplotlib`, `scikit-learn` |
| `Lab3_Logistic_Model.ipynb` | Logistic regression and the impact of class imbalance using the Titanic dataset |
| `Lab4_KNN_Regularization.ipynb` | Naive Bayes, regularization, and KNN |
| `Lab5_PCA.ipynb` | Dimensionality reduction with PCA |
| `Lab6_SWM.ipynb` | Support Vector Machines, one-vs-one vs one-vs-rest multiclass classification |
| `Lab7_Neural_Networks.ipynb` | Neural networks in `PyTorch` for a regression task |
| `Lab9_CNN.ipynb` | Convolutional neural networks and the effect of CNN design choices |
| `Lab10_Advanced_NN_Techniques.ipynb` | Advanced deep learning techniques: gradient clipping, optimizers, fine-tuning pretrained models |
| `Lab11_Decision_Trees.ipynb` | Decision tree regression |
| `Lab12_Stacking_Cifar.ipynb` | Ensemble learning, voting, and pretrained models on `CIFAR100` |

## Course trajectory

Based on the course outline, the broader course moves through:

- ML foundations: overfitting, underfitting, bias-variance tradeoff;
- linear and logistic regression, optimization, and evaluation metrics;
- Naive Bayes, KNN, regularization, and cross-validation;
- dimensionality reduction with PCA;
- support vector machines;
- artificial neural networks and CNNs;
- advanced deep learning techniques;
- decision trees and ensemble learning.

The current repository contains the saved lab notebooks from that trajectory and reflects the practical side of the course.

## Datasets and practice format

The labs use a mix of:

- built-in datasets from `scikit-learn`;
- vision datasets such as `MNIST`, `CIFAR10`, and `CIFAR100`;
- external CSV-based datasets used in practice tasks;
- synthetic datasets for visual demonstrations.

Some notebooks are written in a Colab-friendly style and may reference external file paths or downloadable datasets.

## Tech stack

The repository mainly uses:

- `Python`;
- `Jupyter Notebook`;
- `NumPy`, `Pandas`, `Matplotlib`;
- `scikit-learn` for classical machine learning;
- `PyTorch` and `torchvision` for neural networks and vision tasks;
- `TensorFlow` / `Keras` in selected deep learning notebooks.

## Repository structure

```text
.
├── Lab1_Introduction.ipynb
├── Lab2_Basic_Libraries.ipynb
├── Lab3_Logistic_Model.ipynb
├── Lab4_KNN_Regularization.ipynb
├── Lab5_PCA.ipynb
├── Lab6_SWM.ipynb
├── Lab7_Neural_Networks.ipynb
├── Lab9_CNN.ipynb
├── Lab10_Advanced_NN_Techniques.ipynb
├── Lab11_Decision_Trees.ipynb
├── Lab12_Stacking_Cifar.ipynb
└── README.md
```

## How to use

1. Install the core dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn torch torchvision tensorflow jupyter
```

2. Open any notebook locally:

```bash
jupyter notebook
```

3. Run the labs one by one depending on the topic you want to study.

If a notebook expects a CSV file or Colab-style path, adjust the data path before running it locally.
