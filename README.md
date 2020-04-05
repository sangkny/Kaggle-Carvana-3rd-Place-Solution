# UNet Practice and Applications
```
this repository came from the following 3rd place of kaggle competition
Main purpose of this practice is to apply Unet to simple binary segmentation
# tests on py36-pytor11-TF-gpu-office.yml
- python 3.6
- pytorch-gpu 1.12.0
- tensorflow-gpu 1.10.2
- keras-gpu 2.2.4 (downgraded)
## updates
- 
- 

ReduceLROnPlateau(monitor='valdicecoef',
factor=0.2,
patience=3,
verbose=1,
epsilon=1e-4,
mode='max')
I used above settings, but I think it is better to use validation loss as metrics.

```

# Kaggle-Carvana-3rd-place-solution

Implementation of U-Net + Dilated Convolution. Network detail is shown on below figure.
I used this network in "Carvana-Image-Masking-Challenge-Competition".

![network](./network.png)

## model.py / model_pytorch.py
A script of model definition.

## losses.py
A script of loss functions definition.
