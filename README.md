# Generative-Networks
This repository contains jupyter notebooks with generative models implemented in tensorflow 2.0.0a0.

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

## Implemented Autoencoder
- [Variational Autoencoder](https://github.com/steven-mi/Tensorflow-2.0-Generative-Adversarial-Networks/blob/master/variational-autoencoder.ipynb)

## Implemented GANs
- [Simple Generative Adversarial Network](https://github.com/steven-mi/Tensorflow-2.0-Generative-Adversarial-Networks/blob/master/simple-generative-adversarial-network.ipynb)
- [Deep Convolutional Generative Adversarial Network](https://github.com/steven-mi/Tensorflow-2.0-Generative-Adversarial-Networks/blob/master/deep-convolutional-generative-adversarial-network.ipynb)

- [Wasserstein Gernerative Adversarial Network](https://github.com/steven-mi/Tensorflow-2.0-Generative-Adversarial-Networks/blob/master/wasserstein-generative-adversarial-network.ipynb)

## TODO
- Documentation of VAE
- Documentation of Simple GAN
- Documentation of Deep Convolutional GAN
- Documenation of Wasserstein GAN
- Implementation of other GANs
