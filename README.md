# Generative-Adversarial-182-Networks-Research
# Anime Face Generation Using Generative Adversarial Networks (GANs)

This project is dedicated to developing and applying Generative Adversarial Networks (GANs) for generating anime faces. Recognized for their capability to produce highly realistic images, GANs are explored here for their potential in anime-style imagery.

## Table of Contents
- [Background](#background)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Limitations and Future Work](#limitations-and-future-work)
- [References](#references)
- [Contact](#contact)

## Background

GANs have marked a significant advancement in image generation, especially in creating lifelike human faces. This project takes cues from innovations such as NVIDIA's StyleGAN and applies GANs to anime-style image generation, aiming to capture the distinctive artistic styles of anime and cartoons.

## Methodology

### Training Data
The Anime Face Dataset NTU-MLDS from Kaggle, featuring 36,740 anime face images, is used for training.

### Preprocessing
Images are cropped, resized to 64x64 pixels, and normalized to improve training efficiency.

### Architecture
Our GAN model includes a generator and a discriminator, each consisting of convolutional layers, batch normalization, and activation functions.

### Test Data
The model is evaluated using the CAT dataset from Kaggle.

## Installation

Set up the project environment as follows:

```bash
git clone https://github.com/DH-davidhuang/anime-face-gan.git
cd anime-face-gan
# Follow the steps for environment setup and dependencies installation
```

For a comprehensive collection of all trained models, access the following Google Drive link: [Trained Models Collection](https://drive.google.com/drive/folders/1FuDzWTpHcbuszwcbKeYdc0LNQ8_9gw0x?usp=sharing). These models are also preloaded into a Google Colab, detailed under the section 'finetuning GANs'.
