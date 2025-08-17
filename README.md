Explainable AI: Visualizing CNN Learning
📌 Abstract

This repository explores explainable AI techniques for understanding how Convolutional Neural Networks (CNNs) learn and represent features during training. Deep learning models often behave like black boxes, and these notebooks aim to provide insights into their internal workings by visualizing activations, reconstructions, and interpretability methods.

By using feature visualization, deconvolution, and overlay techniques, the notebooks highlight the hierarchical feature learning process of CNNs, from low-level edge detectors to high-level semantic representations. This enhances model transparency, improves interpretability, and aids in debugging CNN architectures.

📂 Contents
1. cnn_vis_v2.ipynb

Implements CNN visualization techniques to observe the learned feature maps.

Demonstrates how convolutional layers extract spatial and semantic patterns.

Provides step-by-step visualization of activations across different layers.

Useful for understanding progressive feature learning in CNNs.

2. deconvdeepdreamoverlayfeatreconstruction.ipynb

Extends visualization with advanced explainability methods:

Deconvolutional Networks (DeconvNet): Back-projects activations to input space for interpretability.

DeepDream: Enhances learned features to make patterns more visible.

Overlay Reconstructions: Combines activations with input images for clarity.

Helps analyze how specific features influence model predictions.

Serves as a practical guide for feature reconstruction and interpretability.

🎯 Purpose

These notebooks serve as a mini-framework for CNN explainability, designed for:

Students & Researchers – to better understand CNN internals.

Practitioners – to debug models and ensure interpretability.

Educators – to demonstrate feature visualization techniques interactively.
