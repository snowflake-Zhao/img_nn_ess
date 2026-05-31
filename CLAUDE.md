# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This repository is a collection of educational tutorials focused on image classification using PyTorch. It guides users from basic Multilayer Perceptrons (MLP) to advanced Convolutional Neural Network (CNN) architectures.

## Tech Stack
- **Language**: Python 3.8
- **Key Libraries**: 
  - PyTorch 1.7
  - Torchvision 0.8
  - Matplotlib 3.3
  - Scikit-learn 0.24

## Architecture and Structure
The repository is structured as a sequence of tutorials:
- **Tutorial Notebooks**: Located in the root directory (e.g., `1_mlp.ipynb` through `5_resnet.ipynb`). These are designed to be run sequentially.
- `assets/`: Contains images and visualization files used in the notebooks.
- `data/`: Stores datasets, such as the MNIST dataset.
- `misc/`: Contains additional experimental notebooks and utility scripts (e.g., dogs-vs-cats data processing).
- `model/`: Directory for storing trained model weights (`.pth` files).

## Development Guidelines
- **Notebook Execution**: Since the project consists of Jupyter notebooks, development primarily involves executing cells within an environment meeting the tech stack requirements.
- **Data Handling**: Datasets are typically expected to be in the `data/` directory.
- **Model Persistence**: Save trained model weights as `.pth` files in the `model/` directory.
