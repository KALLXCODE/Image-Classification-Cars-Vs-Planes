# Image-Classification-Cars-Vs-Planes

ConvMixer is a recently proposed architecture that is similar to the MLP-Mixer in many ways but uses standard convolution layers instead of fully-connected layers. The use of standard convolution layers provides several benefits, including better efficiency and more flexibility in designing the architecture.

In ConvMixer, the use of BatchNorm instead of LayerNorm is another key difference from MLP-Mixer. While LayerNorm is commonly used in ViTs and MLP-Mixers, BatchNorm is more commonly used in convolutional neural networks (CNNs) and can help to reduce internal covariate shift during training.

ConvMixer also uses two types of convolution layers, depthwise and pointwise convolutions, to mix spatial and channel-wise information. The depthwise convolutions are used to mix spatial locations of the input image, while the pointwise convolutions are used to mix channel-wise information across the patches.

Finally, the use of larger kernel sizes in ConvMixer allows for a larger receptive field, which can be beneficial for processing larger images or capturing more global features in the input.

Overall, ConvMixer represents an interesting new approach to designing image classification models that combines ideas from both MLP-Mixer and CNNs.

![yF8actg](https://user-images.githubusercontent.com/71633926/233623125-15825e16-1269-4592-8164-666989561707.png)
