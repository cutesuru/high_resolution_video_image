# Creating High resolution videos and images
Used a cnn model to create high resolution videos and images .

## Documentation ##
Pre-configured weights are used in this network.Here is the pth file [pre_weight](superres_epoch100-44c6958e.pth)

Framework: Pytorch
Input image size: (224 x 224)
Output image size: (672 x 672)
Libraries Used:
* Numpy
* Matplotlib
* OpenCV

## References ##
1)Model used is taken from [Superresolution using an efficient sub-pixel convolutional neural network](https://github.com/pytorch/examples/tree/master/super_resolution)

## Example ##
```out=torch_model(img_y)```
[images](high_resolute_image.jpg)
