# Connect Four - Supervised Learning Project

## Overview

Welcome to the **Connect Four** project repository. This project is a university assignment aimed at simulating an agent that plays Connect Four using neural networks. The core objective is to investigate and compare the performance of different neural network architectures in replicating the moves of a pre-trained AI agent.

The project is documented in detail in the provided PDF dissertation and executed using a Google Colab notebook. Below are the key components and instructions for exploring the project.

## Contents

- **[[Connect-four.ipynb](Connect-four.ipynb)](https://github.com/enrischia/Connect-Four/blob/main/Connect_Four.ipynb)**: Google Colab notebook containing the code for simulating Connect Four with neural networks.
- **[connect_four.pdf](connect_four.pdf)**: Dissertation detailing the research and findings of this project.

## Abstract

This study explores the ability of neural network models to replicate the moves of a pre-trained AI agent in Connect Four. It involves data processing, removal of duplicates, and preprocessing for machine learning algorithms. Two neural network architectures are evaluated:

1. **MultiLayer Perceptron (MLP)** - A simple yet powerful network with fully connected layers.
2. **Convolutional Neural Network (CNN)** - A network utilizing convolutional layers to capture spatial hierarchies in the game grid.

The project focuses on:
- Data preprocessing and feature engineering.
- Training and evaluating both MLP and CNN models.
- Analyzing performance metrics and confusion matrices.

## Objectives

- **Feature Engineering**: Augmenting and preprocessing game data to improve model performance.
- **Model Comparison**: Evaluating MLP and CNN in terms of accuracy, loss, and overall performance.
- **Performance Metrics**: Analyzing confusion matrices, precision, recall, and accuracy.

## Getting Started

### Prerequisites

To run the code in the notebook, ensure you have:
- Python 3.x installed
- Necessary libraries (e.g., TensorFlow/PyTorch, NumPy, pandas) installed. The notebook will guide you on library installations.

### Running the Notebook

1. Open [Connect-four.ipynb](Connect-four.ipynb) in Google Colab or Jupyter Notebook.
2. Follow the instructions within the notebook to execute the code cells and explore the results.

### Viewing the Dissertation

- Download and review [connect_four.pdf](connect_four.pdf) for a comprehensive understanding of the project's methodology, results, and analysis.

## Results and Discussion

- **MLP Performance**: Analyzed with various input features and hyperparameters to evaluate its classification performance.
- **CNN Performance**: Assessed for its effectiveness in capturing spatial patterns and improving accuracy and loss metrics.
