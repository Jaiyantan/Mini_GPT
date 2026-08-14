# Mini_GPT

A lightweight implementation of a Generative Pre-trained Transformer (GPT) model, designed for educational purposes and efficient experimentation.

## Overview
`Mini_GPT` provides a simplified, readable codebase to help developers and students understand the architecture of Transformer-based models. It includes the core components required to build and train a decoder-only language model from scratch using PyTorch.

## Features
*   **Transformer Architecture:** Clean implementation of self-attention mechanisms and feed-forward layers.
*   **Modular Design:** Easy to modify components for experiments with different model depths or hidden sizes.
*   **Efficient Training:** Optimized for quick iterations on small-to-medium-sized datasets.

## Prerequisites
Ensure you have the following installed:
*   Python 3.8+
*   PyTorch
*   (Optional) CUDA-enabled GPU for faster training

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jaiyantan/Mini_GPT.git
   cd Mini_GPT
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
*   **Training:** Run the training script to begin learning from your text corpus.
    ```bash
    python train.py
    ```
*   **Inference:** Use the generation script to sample text from your trained model.
    ```bash
    python generate.py
    ```

## Project Structure
*   `model.py`: Definitions for the GPT architecture.
*   `train.py`: Training loop and configuration.
*   `generate.py`: Scripts for text generation.
*   `data/`: Directory for input text datasets.


## License
MIT License
