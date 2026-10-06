CIFAR 10 CNN Comparison Report
CAP4453 Assignment 2  

# Implementation
## Dataset and preprocessing
The images use CIFAR-10 which contains 32 x 32 color images in 10 classes. The training data is divided into training and validation subsets using a seeded 80/20 split. Both models use the same split and a batch size of 64.
## Model architectures
The two-layer convolutional neural network has two 3 x 3 convolutional layers with 16 and 32 output channels.
The three-layer convolutional neural network has three 3 x 3 convolutional layers with 16, 32, and 64 output channels.
## Training configuration

Both models are trained for 30 epochs using Adam with a learning rate of 5 × 10⁻⁴ and weight decay of 5 × 10⁻⁴.

