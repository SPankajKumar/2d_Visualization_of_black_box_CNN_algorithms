# 2d_Visualization_of_black_box_CNN_algorithms
🧠 Explainable AI for CNN Visualization

This repository contains two Jupyter notebooks that demonstrate Explainable AI (XAI) techniques for understanding the learning process of Convolutional Neural Networks (CNNs). The focus is on visualizing what the network learns during training, making the "black box" of deep learning more interpretable.

📌 Overview

CNNs are highly effective in computer vision tasks, but they are often criticized for being opaque—it’s difficult to understand why they make certain predictions.
This project applies visualization techniques to uncover the inner workings of CNNs by:

Reconstructing feature maps from different layers.

Generating deep dream–like overlays to highlight salient features.

Visualizing convolutional filters and their evolution.

Exploring interpretability techniques to see how CNNs perceive images.

Together, these methods give insight into the hierarchical feature extraction that CNNs perform, starting from edges and textures to complex shapes.

📂 Contents
🔹 cnn_vis_v2.ipynb

Implements CNN visualization techniques.

Displays feature activations layer by layer.

Highlights how filters evolve and what features they capture.

Useful for understanding progressive abstraction in CNNs.

🔹 deconvdeepdreamoverlayfeatreconstruction.ipynb

Uses deconvolution, deep dream, and overlay methods.

Reconstructs input images from intermediate feature representations.

Provides an intuitive look into what the CNN emphasizes.

Combines multiple interpretability techniques for deeper insights.

🛠️ Methodology

The project leverages Explainable AI techniques including:

Deconvolutional Networks → Mapping activations back to pixel space.

Deep Dream Visualizations → Enhancing learned patterns to see what excites neurons.

Feature Reconstruction → Rebuilding images from intermediate CNN layers.

Activation Maps → Showing which regions contribute most to predictions.

These methods make it possible to see how a CNN transforms raw input into high-level decisions.
