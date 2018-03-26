# dogs_vs_cats
该项目是来自己于优达学城机器学习进阶学位毕业项目--[猫狗大战](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition)。其数据集是来自于Kaggle Competition。
我使用基于Tensorflow的Keras库搭建Pre-trained的ResNet50、InceptionV3、Xception和Inception Resnet v2等四个模型进行迁移学习；

该模型是在谷歌云上进行训练，其中显卡为NVIDIA Tesla P100，内存为32G。由于模型过多，在谷歌云上训练时间大概是4小时。

训练结束后，Inception Resnet v2模型在Kaggle测试集上进行预测的得分最高，为0.03942。
