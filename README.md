# Waymo Trajectory Prediction

This project leverages the **Waymo Open Motion Dataset** to train and evaluate machine learning models for agent trajectory prediction. It focuses on comparing the performance of modern neural network architectures against traditional physics-based baseline models.

## Repository Structure

- **`waymo_baseline.ipynb`**: Contains the implementation and evaluation of the physics-based models (e.g., constant velocity/acceleration) alongside a foundational Multi-Layer Perceptron (MLP) neural network.
- **`waymo_transformer.ipynb`**: Contains the architecture, training loop, and evaluation for an advanced Transformer-based neural network model designed to capture complex temporal and spatial dependencies in motion data.

## Models Compared

1. **Physics-Based Baselines**: Traditional kinematic models used as a benchmark for trajectory forecasting.
2. **MLP (Multi-Layer Perceptron)**: A standard feedforward neural network approach.
3. **Transformer**: An attention-based sequence model to handle complex agent interactions and sequential motion data.

## Getting Started

To run the codebase, ensure you have the `waymo-open-dataset` API installed along with your preferred deep learning framework (e.g., TensorFlow or PyTorch). Run the Jupyter notebooks sequentially to train the models and view the comparative results.