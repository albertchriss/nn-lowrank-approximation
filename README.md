# Neural Network Optimization with SVD

This repository contains the implementation and analysis for the paper **"Penerapan Singular Value Decomposition untuk Optimasi Neural Networks melalui Low-Rank Approximation"**.

The notebook demonstrates how **low-rank approximation** using **Singular Value Decomposition (SVD)** can optimize neural networks by:
- Reducing memory usage.
- Decreasing computation time.
- Maintaining comparable accuracy to the original model.

Key components:
- **Original Model**: A baseline neural network implemented using TensorFlow/Keras.
- **Low-Rank Approximation**: Decomposing weight matrices into low-rank representations.
- **Performance Comparison**: Evaluating accuracy, memory usage, and training/inference time across different ranks.

This work provides insights into making the deployment of neural networks more efficient, particularly for resource-constrained environments.

---