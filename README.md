# Pytorch modules with sane defaults for model prototyping
This is a number of custom pytorch modules with sane default parameters that I find useful in model prototyping. Contains:

1. 2D U-Net with different options for how the feature maps are upsampled (to prevent checkerboard artifacts.)
2. 3D U-Net
3. 2D downsampling network
4. 2D upsampling network with different options for how the feature maps are upsampled (to prevent checkerboard artifacts.)
5. A 2D conv layer that pads to keep the spatial dimensions of the feature map constant, with reflection padding.
