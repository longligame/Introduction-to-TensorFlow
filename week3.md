# Week3 Enhancing Vision with Convolutional Neural Networks

**`Convolution Layer`**
- 滑动一个卷积模版 (filter) ，对图片点乘得到新的灰度


<img width="1280" alt="con" src="https://user-images.githubusercontent.com/41643043/57127169-1d0d3a80-6dc2-11e9-8cbd-0cf7495e9c00.png">



**`Pooling Layer`**
- 压缩图片，从四个pixel中选取一个最大的


<img width="1280" alt="pooling" src="https://user-images.githubusercontent.com/41643043/57127170-1d0d3a80-6dc2-11e9-99a5-ef8470987090.png">





**使用`convolution layer`和`pooling layer`**
- 第一行代码需要```input_shape```
- 倒数第三行，代表将图片化成一行列向量输入进去



![](https://user-images.githubusercontent.com/41643043/57127644-affaa480-6dc3-11e9-9426-9541b1c777cb.png)


**使用 `model.summary()`来查看整个 `model` 的历程**

![](https://user-images.githubusercontent.com/41643043/57127649-b25cfe80-6dc3-11e9-8d8a-a47ed7c7043f.png)



