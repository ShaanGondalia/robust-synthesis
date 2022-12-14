# robust-synthesis
Implements image synthesis with a robust classifier based on [Computer Vision with a Single (Robust) Classifier](https://arxiv.org/pdf/1906.09453.pdf). Implements image generation, inpainting, image-to-image translation, and super-resolution on CIFAR-10 and [ImageNette](https://github.com/fastai/imagenette) images. This repo is meant to be run in Google Colab.

## Installation
1. Clone this repository with `git clone git@github.com:ShaanGondalia/robust-synthesis.git`.
1. Visit the [authors' GitHub repository](https://github.com/MadryLab/robustness_applications#running-the-notebooks) to download the pre-trained CIFAR-10 model. Add this model to the `models` folder in this repository.
	- If you want to use ImageNette, download the pre-trained ImageNet model instead.
1. Upload the root directory of the repository to your Google Drive, so that Colab can access your code.
1. Change the `WORKDIR` constant in `main.ipynb` to the path of your repository in Google Drive.

### ImageNette
Download the ImageNette dataset from [here](https://github.com/fastai/imagenette). Add the downloaded data folder to the `robust-synthesis/data` folder. Make sure the folder is called `imagenette`.

## Usage
Once the initial setup is complete, run `main.ipynb` in Google Colab. CUDA is required. See specific sections of the notebook for each synthesis technique.
