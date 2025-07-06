 Lab 03: TensorFlow vs. PyTorch

This project demonstrates the training of a neural network on the MNIST dataset using both TensorFlow and PyTorch. It also covers the conversion of the trained models to TFLite (for TensorFlow) and ONNX (for PyTorch) for deployment. A custom training loop using tf.GradientTape is implemented for TensorFlow to showcase more granular control over the training process, alongside a performance optimization demonstrating @tf.function.

---

## Repository Contents

The full source code for this project is available on GitHub at:
**https://github.com/ronak22022003/tensorflow-and-pytorch-lab03**

This repository includes:

* *TensorFlow and PyTorch scripts:* The .ipynb file contains the complete code for both framework implementations.
* *Instructions for running the code:* (This README itself serves as an initial guide, and detailed steps are within the notebook.)
* *Logs of training and evaluation:* The output logs from training and evaluation are included within the .ipynb file.
* *Documentation and usage guidelines:* This README provides an overview, and comments/markdown within the notebook offer further documentation.

---

## Project Overview (From Lab Description)

* *Goal:* Train a model on MNIST in both TensorFlow and PyTorch, convert to TFLite and ONNX.
* *Key Feature:* Use tf.GradientTape for TensorFlow custom training loop.

---

## How to Run

1.  *Clone the Repository:*
2.  *Open in Google Colab (Recommended):*
    * Go to [Google Colab](https://colab.research.google.com/).
    * Click File > Upload notebook.
    * Select the Lab_03_Tensorflow_and_PyTorch.ipynb (or similar name if you renamed it) file from your cloned repository.
    * Alternatively, go to File > Open notebook > GitHub and search for your repository.
3.  *Install Dependencies:* All necessary libraries are standard in Colab or installed within the notebook (!pip install onnx).
4.  *Run Cells:* Execute each cell sequentially. The notebook will download datasets, train models, and convert them.

---

## Output Logs (Included in the notebook)

The notebook cells contain the direct output logs, including:
* MNIST dataset download progress.
* TensorFlow model.fit training progress (epochs, loss, accuracy).
* PyTorch training loop output (training time).
* Evaluation metrics (test accuracy).
* TFLite conversion messages.
* ONNX installation and export messages.

---

## Models Exported

Upon successful execution, the following model files will be generated in your Colab environment (and can be downloaded from there):
* model.tflite (from TensorFlow)
* model.onnx (from PyTorch)
