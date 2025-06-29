# cGAN-Text-To-Image-Bird-Generation

Text-to-Image Generation with Birds using Conditional GANs (cGAN).

## Overview

This project demonstrates generating realistic bird images from textual descriptions using a Conditional Generative Adversarial Network (cGAN). All code and experiments are implemented in Jupyter Notebook, with a comprehensive walkthrough provided for ease of understanding and reproducibility.

You can also view the project and its results on Kaggle:  
[Text-to-Image Generation with Birds using cGAN on Kaggle](https://www.kaggle.com/code/emanafi/text-to-image-generation-with-birds-using-cgan)

## Features

- Conditional Generative Adversarial Network (cGAN) for image synthesis.
- End-to-end workflow from data loading to image generation, training, and evaluation.
- Example-driven development using the CUB-200-2011 Birds dataset and text embeddings.
- Visualizations of generated images vs. input text descriptions.
- All code contained in a single Jupyter Notebook for simplicity.

## Project Structure

```
.
├── submission.ipynb           # Main notebook with code, explanations, and results
├── README.md                  # Project documentation
```

## Getting Started

### Prerequisites

- Python 3.7+
- Kaggle
- [Keras](https://keras.io/) / [TensorFlow](https://www.tensorflow.org/)
- numpy, pandas, matplotlib, PIL, and other standard Python scientific libraries

### Dataset

The project uses the [CUB-200-2011 Birds dataset](https://www.kaggle.com/datasets/mohamedihebhergli/assignment-3-cub200-2011), which includes images and text captions.  

## Usage

1. Open `submission.ipynb` in Kaggle.
2. Follow the notebook step-by-step:
   - Data loading and preprocessing
   - Model architecture
   - Training procedure
   - Image generation and evaluation
3. Modify parameters or experiment with your own text inputs to generate new bird images.

## References

- [Kaggle Project Link](https://www.kaggle.com/code/emanafi/text-to-image-generation-with-birds-using-cgan)
- [Original cGAN Paper](https://arxiv.org/abs/1411.1784)
- [CUB-200-2011 Birds dataset](https://www.kaggle.com/datasets/mohamedihebhergli/assignment-3-cub200-2011)
