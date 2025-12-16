# COMP6012 – CIFAR-10 Deep Learning Project

## Overview

This project studies the effect of **training data size**, **model architecture**, **regularization**, and **training acceleration techniques** on image classification using the **CIFAR-10 dataset**.

Implemented models:

* MLP
* CNN (**Best performing**)
* ResNet-18

---

## Files

* `21108697_DipeshShrestha_COMP6012.ipynb` – Main notebook (training & experiments)
* `comp6012-REPORT.pdf` – Final report
* `README.md` – Project instructions

---

## Requirements

* Python 3.8+
* PyTorch
* torchvision
* numpy
* matplotlib

Install dependencies:

```bash
pip install torch torchvision numpy matplotlib
```

---

## How to Run

1. Open terminal in the project directory
2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open the notebook:

```text
21108697_DipeshShrestha_COMP6012.ipynb
```

4. Run all cells from top to bottom

> **Note:** A CUDA-enabled GPU is recommended for faster training but is not required.

---

## Dataset

* CIFAR-10 is automatically downloaded using `torchvision`
* No manual dataset setup is required

---

## Best Model

* **CNN**
* Final Accuracy: **62.47%**
* Best balance between accuracy and training time

---

## Course Information

* **Unit:** COMP6012 – Machine Learning
* **Institution:** Curtin University
* **Student:** Dipesh Shrestha