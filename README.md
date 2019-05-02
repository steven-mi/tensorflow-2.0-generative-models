# Generative-Adversarial-Networks-Experiments
This repository contains experiments with GANs with Tensorflow 2.0.0a0. Still working on the repository.

## Getting Started (with Docker)
Pull from the official tensorflow dockerhub account the `tensorflow:2.0.0a0` container.
- with GPU:
  ```bash
  nvidia-docker run -it --rm tensorflow/tensorflow:2.0.0a0-gpu-py3-jupyter bash
  git clone https://github.com/steven-mi/Tensorflow-2.0-Generative-Adversarial-Networks.git
  ```
- without GPU
  ```bash
  docker run -it --rm tensorflow/tensorflow:2.0.0a0-py3-jupyter bash
  git clone https://github.com/steven-mi/Tensorflow-2.0-Generative-Adversarial-Networks.git
  ```

## Implemented GANs

## TODO
- README.md
- Documentation of VAE
- Documentation of Simple GAN
- Documentation of Deep Convolutional GAN
- Implementation of other GANs
