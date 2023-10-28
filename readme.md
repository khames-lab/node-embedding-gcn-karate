# Graph Convolutional Network (GCN) for Karate Club Dataset

This repository contains code for training a Graph Convolutional Network (GCN) on Zachary's karate club network and visualizing node embeddings in a 2D space.

## Introduction

The Karate Club dataset is a classic social network dataset representing the interactions between members of a karate club. This project uses PyTorch Geometric to build a GCN model and visualize the embeddings of the karate club members.

## Requirements

- Python 3.x
- PyTorch
- PyTorch Geometric
- NetworkX
- Matplotlib
- Scikit-Learn

Install the required dependencies using the following command:


## Model Architecture

The GCN model consists of two graph convolutional layers with hyperbolic tangent (tanh) activation functions and a linear classifier. The model is trained using Cross-Entropy Loss and the Adam optimizer.

The script will train the model and generate a scatter plot of node embeddings using t-SNE. The plot will be displayed or saved as an image file.

