# fcn
voc dataset,semantic segmentation
##  数据集准备
下载VOC数据集，大概1~2G，记不太清楚了，写一个转换脚本，convert_fcn_dataset.py,将数据打包成tf_record形式
##  fcn8s实现
在vgg网络的基础上，修改fcn16s,本仓库修改后为train.py，修改的具体步骤请看本人的总结
##  其他需要准备的
下载Vgg16的预训练模型，训练时需指定路径
## 图像分割综述及总结
总结近年实例分割和语义分割的进展及各个方案的思考，语言简洁精炼，读者能有很大收获！
###  模型tinymind地址
https://www.tinymind.com/qq-25646217/fcn8s/code 欢迎复制模型进行测试
###    更早一些的项目
如densenet复现，minist卷积神经网络，cnn前向网络练习等等在本人码云地址https://gitee.com/JueDiDaTaoSha
