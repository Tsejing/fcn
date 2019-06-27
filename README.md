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
