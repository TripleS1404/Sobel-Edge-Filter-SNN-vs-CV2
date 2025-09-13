# Sobel-Edge-Filter-SNN-vs-CV2

This project demonstrates a spiking neural network (SNN) implementation of the Sobel edge detection algorithm. Using PyTorch and SpikingJelly, the model applies rate-coded spiking inputs to Sobel convolution filters followed by leaky integrate-and-fire (LIF) neurons. The outputs are compared against classical Sobel filters and OpenCV’s Sobel implementation.

# Main Features of the Project

* Rate coding for converting grayscale images into spike trains 
* Custom LIF neuron module in PyTorch 
* SNN Sobel edge detection in X and Y directions
* Edge magnitude computation from spiking outputs
* Comparison with classical Sobel and OpenCV Sobel
* Visualization of original image, SNN edges, and classical edges
