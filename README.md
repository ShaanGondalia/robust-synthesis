# robust-synthesis
Image Synthesis with a Robust Classifier based on "Computer Vision with a Single (Robust) Classifier". Implements image generation, inpainting, image-to-image translation, and super-resolution on CIFAR-10 images. This repo is meant to be run in Google Colab.

## Installation
1. Clone this repository with `git clone git@github.com:ShaanGondalia/robust-synthesis.git`
1. Visit the [original GitHub repository](https://github.com/MadryLab/robustness_applications#running-the-notebooks) to download the pre-trained CIFAR-10 model. Add this model to the `models` folder in this repository.
1. Install the latest version of the [`robustness`](https://github.com/MadryLab/robustness) python library. Move the `robustness/robustness` folder into the root of this repo (i.e. `./robust-synthesis/robustness`)
1. Upload the repository to Google Drive, so that Colab can access your code.
1. Change the `WORKDIR` constant in `main.ipynb` to the path of your repository in Google Drive.

## Usage
Once the initial setup is complete, run `main.ipynb` in Google Colab. CUDA is required. See specific sections of the notebook for each synthesis technique



Move downloaded files to drive folder

Add inline pip installs for requirements (cox, tensorboardX)
Change DATA to CIFAR





