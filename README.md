# Image-Denoising
## Overview

Denoising is a crucial task in image processing to remove noise while preserving important features. This repository explores different denoising techniques implemented using both traditional and deep learning approaches.

## Techniques

### Wavelet Denoising

Wavelet denoising applies the wavelet transform to the noisy image and then applies thresholding to the wavelet coefficients to remove noise.

### Wiener Filter

The Wiener filter is a linear filter used for signal and image denoising. It minimizes the mean square error between the estimated signal and the original signal.

### MAP Estimator

The Maximum A Posteriori (MAP) estimator is a statistical method used to estimate the most likely true image given a noisy observation. It involves maximizing the posterior probability of the image given the observed data.

### BM3D Algorithm

The Block-Matching and 3D filtering (BM3D) algorithm is a state-of-the-art denoising technique that operates in two steps: collaborative filtering and non-local means filtering.

### Denoising Autoencoder (Deep Learning Model)

Denoising Autoencoder is a deep learning model trained to remove noise from input images. It consists of an encoder and a decoder network trained to reconstruct clean images from noisy inputs.
