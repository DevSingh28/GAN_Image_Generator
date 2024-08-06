# GAN_Image_Generator
A Image Generator Model using GAN

# Cat Images GAN

This repository contains the implementation of a Generative Adversarial Network (GAN) for generating cat images. The GAN consists of a Generator and a Discriminator, trained on a dataset of cat images.

## Requirements

To run this project, you need to have the following installed:

- Python 3.x
- PyTorch
- Torchvision
- Matplotlib
- Numpy
- Kaggle CLI (for downloading the dataset)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/cat-images-gan.git
    cd cat-images-gan
    ```

2. Install the required packages:

    ```sh
    pip install torch torchvision matplotlib numpy kaggle
    ```

3. Set up Kaggle API:

    - Go to your Kaggle account and create an API token.
    - Place the `kaggle.json` file in your home directory under the `.kaggle` folder:

    ```sh
    mkdir ~/.kaggle
    cp kaggle.json ~/.kaggle/
    chmod 600 ~/.kaggle/kaggle.json
    ```

4. Download the cat dataset from Kaggle:

    ```sh
    kaggle datasets download -d crawford/cat-dataset
    unzip cat-dataset.zip -d cats
    ```
