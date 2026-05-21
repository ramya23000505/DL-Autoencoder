# DL- Convolutional Autoencoder for Image Denoising

## AIM
To develop a convolutional autoencoder for image denoising application.

## Problem Statement and Dataset

This code implements a Denoising Autoencoder using PyTorch to clean noisy images from the MNIST dataset. It uses a convolutional neural network architecture, where the encoder compresses the input image into a lower-dimensional representation, and the decoder reconstructs the original image from this compressed form. To train the model to remove noise, Gaussian noise is added to the clean images, and the network learns to recover the original from the noisy version. The training process uses Mean Squared Error (MSE) as the loss function to measure the reconstruction error and the Adam optimizer to update the model weights. The autoencoder is trained over multiple epochs using mini-batches of data for efficiency. After training, the model's performance is visually evaluated by displaying the original, noisy, and denoised images side by side.

## DESIGN STEPS
### STEP 1: 

Load MNIST data and add noise to images.

### STEP 2: 

Build a convolutional autoencoder.

### STEP 3: 


Train the model with noisy images, minimizing MSE loss.
### STEP 4: 

Update weights using backpropagation.

### STEP 5: 

Test the model and visualize original, noisy, and denoised images.

### STEP 6: 

Repeat through multiple epochs for better denoising performance.

## PROGRAM

### Name: RAMYA R

### Register Number: 212223230169

```python
# Autoencoder Definition
class DenoisingAutoencoder(nn.Module):
    def __init__(self):



# Initialize model

# Training function

# Visualization function


```

### OUTPUT

### Model Summary
Include your model summary

### Training loss

## Original vs Noisy Vs Reconstructed Image
Include a few sample images here.

## RESULT
Thus, a convolutional autoencoder for image denoising application has been developed.
