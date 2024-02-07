# Project: Neural Style Transfer 🎨

Neural Style Transfer is a fascinating approach to modify an image, blending the content of one image with the style of another. This technique involves utilizing a pretrained convolutional neural network (CNN) to compute a loss function, which guides the transformation process. Originating from the paper "A Neural Algorithm of Artistic Style" by Leon Gatys, Alexander Ecker, and Matthias Bethge, this method leverages the representations learned by the CNN to measure both content and style similarities between images.

## Overview
In this project, we will employ the VGG19 CNN architecture, a powerful model pretrained on large-scale image recognition tasks, such as the ImageNet dataset. Our objective is to generate an image that combines the content of a given input image with the style of a reference image. To achieve this, we will utilize the following key concepts:

- Content Image: The input image whose content we aim to preserve in the generated image.
- Style Image: The reference image whose style we wish to emulate in the generated image.
- Loss Function: Comprising of content and style components, the loss function quantifies the disparity between the generated image and both the content and style images.
- Gram Matrix: Calculated from the feature maps of CNN layers, the Gram matrix captures style information by computing correlations between different feature maps.
- Custom Models in Keras: Utilizing the Keras Functional API and Subclassing API, we will construct custom models to compute CNN activations and Gram matrices efficiently.
- TensorFlow: Leveraging TensorFlow functions and automatic differentiation, we will implement custom training loops to optimize the generated image.

## Objectives
- Understand the theory behind neural style transfer and its application in deep learning.
- Implement neural style transfer using the VGG19 CNN architecture and TensorFlow/Keras.
- Experiment with different content and style images to observe the artistic effects.
- Explore advanced techniques such as variational neural style transfer and adversarial style transfer.
- Optimize the implementation for performance and scalability.

By engaging in this project, I gained valuable insights into advanced usage of Keras and TensorFlow, as well as a deeper understanding of convolutional neural networks and their applications in computer vision and artistic expression. 
