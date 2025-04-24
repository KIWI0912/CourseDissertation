# Diffusion Models and GANs

This repository contains implementations of Diffusion Models and Generative Adversarial Networks (GANs) using PyTorch. The code demonstrates training on the Fashion-MNIST dataset and includes both GAN and DDPM (Denoising Diffusion Probabilistic Models) implementations.

## Contents

- `main.ipynb`: Jupyter Notebook with the implementation of GAN and DDPM.
- `environment.yml`: Conda environment file to set up the required dependencies.

## Requirements

- Python 3.8 or higher
- PyTorch
- torchvision
- numpy
- matplotlib
- tqdm

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/KIWI0912/Diffusion_Models_and_GANs.git
   cd Diffusion_Models_and_GANs
   ```

2. Create a conda environment and install dependencies:
   ```bash
   conda env create -f environment.yml
   conda activate diffusion_gan_env
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

## Usage

The notebook includes:
- Data loading and preprocessing for the Fashion-MNIST dataset.
- Implementation of a simple GAN with a generator and discriminator network.
- Implementation of a simple UNet-based DDPM.

## Results

The training results and generated images are saved in the `results` directory.

## License

This project is licensed under the MIT License.
