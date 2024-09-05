# Quantum-Improved-Generative-Adversarial-Networks-QGANs-

This repository contains the implementation of Quantum-Enhanced Generative Adversarial Networks (QGANS) and a classic GAN model for comparison. The project aims to explore the integration of quantum computing into generative adversarial networks (GANs) to address challenges like mode collapse and training instability inherent in classical GANs.

## Project Overview

**Objective:** To demonstrate that quantum-enhanced GANs offer advantages over classical GANs in terms of performance and diversity of generated data.

### Key Components:
1. **Classic GAN Model:** A standard GAN implementation that serves as the baseline for comparison.
2. **Quantum-Enhanced GAN Model (QGANS):** A hybrid model that integrates quantum circuits into the generator of a GAN, utilizing TensorFlow and Google Cirq.

### Files in the Repository:
- **classic gan model .ipynb:** Contains the implementation of the classic GAN model on a small dataset.
- **QGANS model .ipynb:** Contains the implementation of the Quantum-Enhanced GAN model using quantum computing techniques.
  
### Dataset
- **Dataset Used:** CIFAR-10 (You can also switch to smaller datasets like MNIST if you face hardware limitations).
  
### Results:
- **GAN Performance:** Evaluates the performance of both models in terms of generated image quality and training stability.
  
### How to Run the Code:

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
2. Open the respective Jupyter notebooks (classic gan model.ipynb or QGANS model.ipynb) and execute the cells.
Challenges:
The models require significant computational power. Ensure your system has sufficient RAM or use Google Colab to run the notebooks.

Future Work:
Further optimization of quantum circuits in GANs.
Exploration of larger datasets with optimized quantum layers.
   
