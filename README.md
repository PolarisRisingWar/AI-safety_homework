# 作业1
任务：使用cifar10数据集进行图像分类任务  
具体内容：使用Python语言，用jupyter notebook作为编辑器，使用PyTorch框架建立模型，通过torchvision.datasets包加载数据集，最后在测试集上得到了超过随机模型（10%）的准确率结果（49%）。  
<br>
流程：  
1. 通过torchvision.datasets包加载数据集
2. 建立CNN模型，框架为：Conv2d→ReLU→Pool→Conv2d→ReLU→Pool→Linear→Linear→Linear
3. 配置超参
4. 训练epoch轮模型
5. 通过测试集数据检验模型在全部类和各类上的准确率值。
