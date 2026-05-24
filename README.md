# Deep Learning — Jupyter Notebooks

Experiments with TensorFlow and Keras covering neural network fundamentals, CNNs, transfer learning, and sequence models. All notebooks run in a Python virtual environment with no GPU required (CUDA optional for faster training).

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-API-D00000?logo=keras&logoColor=white)
![Jupyter](https://img.shields.io/badge/JupyterLab-3.x-F37626?logo=jupyter&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-22c55e)

---

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install tensorflow jupyterlab matplotlib numpy pandas scikit-learn
jupyter lab
```

GPU support (optional):

```bash
# Requires CUDA 11.x + cuDNN — see https://www.tensorflow.org/install/pip
pip install tensorflow[and-cuda]
```

---

## Notebooks

| Notebook | Topic | Key Concepts |
|---|---|---|
| `01_intro_neural_networks.ipynb` | Feedforward networks | Activations, backprop, gradient descent |
| `02_cnn_image_classification.ipynb` | Convolutional networks | Conv2D, MaxPooling, CIFAR-10 |
| `03_transfer_learning.ipynb` | Pre-trained models | Fine-tuning ImageNet weights, feature extraction |
| `04_rnn_sequence.ipynb` | Sequence modeling | LSTM, GRU, time-series prediction |
| `05_data_augmentation.ipynb` | Training robustness | `ImageDataGenerator`, random flip/rotate/zoom |

---

## Requirements

- Python 3.9+
- TensorFlow 2.x
- JupyterLab 3.x
- NumPy, Matplotlib, scikit-learn
