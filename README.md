# Resnet
pytorch version of resnet

首先下载Cifar-10 数据集：https://pan.baidu.com/s/1I-btaQLxeILA39TcecDVig （提取码：5tk8）
然后将下载的数据解压到data文件下

pip install torch

所有的resnet代码均可直接运行，且均根据Resnet论文原文进行复现

python resnet_13.py

由于Cifar-10中数据集图片大小仅有28*28

因此Resnet-34,50,101 都没有仅12个卷积的Resnet-12准确率更高可达到0.88

若想导入自己数据集只需将代码中的数据导入部分换为自己的即可
