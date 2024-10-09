# Moroccan AI Art Generator

This repository contains an implementation of an AI-powered art generator focused on creating Moroccan-inspired imagery. The project leverages state-of-the-art language models and image generation techniques to produce stunning visual art based on textual descriptions.

## Project Overview

The purpose of this project is to explore and demonstrate the capabilities of AI in generating culturally-specific art. It uses the Stable Diffusion model, a powerful text-to-image generation model, to create images inspired by Moroccan culture, landscapes, and traditions.

## Files

- `Text_to_Image_generation.ipynb`: Jupyter notebook containing the original implementation and experiments.

## Prerequisites

### Software Requirements

- Python 3.7 or higher
- CUDA-capable GPU (for optimal performance)

### Libraries

The following libraries are required to run the project:

- `torch`: PyTorch library for deep learning
- `diffusers`: Hugging Face's library for diffusion models
- `transformers`: Hugging Face's transformers library
- `accelerate`: Library for easy use of accelerators like GPUs
- `matplotlib`: Plotting library for displaying generated images

To install these dependencies, run the following command:
```bash
pip install torch diffusers transformers accelerate matplotlib
