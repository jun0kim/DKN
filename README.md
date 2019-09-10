


# Deformable Kernel Network for Joint Image Filtering
This is the pytorch implementation of our DKN paper (paper link). 
![image](https://user-images.githubusercontent.com/5655912/37342239-53239644-2707-11e8-85b1-9b25c290d81e.png)


## 1. Requirement

Pytorch 0.2.0

Cuda 9.0

Opencv 3.3

PyInn: https://github.com/szagoruyko/pyinn





## 2. Usage

- Depthmap upsampling
> python DepthUpsampling.py --rgb images/0\_rgb.png --depth images/0\_lr.png --k 3 --d 15 --scale 8 --parameter parameter/Depth8x --output images/result.png

- Noise reduction
> python NoiseReduction.py --target images/target.png --guidance images/guidance.png --k 3 --d 15 --parameter parameter/Noise --output images/noise_reduction.png





## 3. Examples
**Depthmap Upsampling**![image](https://user-images.githubusercontent.com/5655912/37327511-fa790b50-26d9-11e8-9f34-2f8b8f9438c1.png)
**Noise Reduction (Flash/No-flash, RGB/NIR)**![image](https://user-images.githubusercontent.com/5655912/37327624-72b3b16a-26da-11e8-9b6f-9c872023fdae.png)
