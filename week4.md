# Week4 Using Real-world Images


挺有意思的视频：[利用`Tensorflow`在非洲检测植物生病的模型](https://www.youtube.com/watch?v=NlpS-DhayQA)


**引入真实世界图片**
- 之前用的数据集都是固定大小的图片，比如28x28，并且是gray的图片
- 现在采用真实世界的图片，大小形状不一，并且通道数也不是1个。

**利用`tensorflow`生成图片**

- `import ImageDataGenerator`

**ImageDataGenerator**
- 在相应文件夹的图片，会自动被打上标签
- 使用```rescale```，可以自动归一化图片
- 使用```target_size```，使图片大小变成多少

<img width="1280" alt="im_gen" src="https://user-images.githubusercontent.com/41643043/57132340-dd4e4f00-6dd1-11e9-8a4f-0a4941b62958.png">

<img width="1280" alt="img_gen" src="https://user-images.githubusercontent.com/41643043/57132664-e25fce00-6dd2-11e9-9c2b-fdda64ee510a.png">


