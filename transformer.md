> **激活函数**

RELU(x) = max(0, x)

sigmod(x) = $\frac{1}{1 + e^{-x}}$

> **损失函数**

均方误差(MSE): 
MSE = $\frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2$

> **线性回归**

> **梯度下降**

> **反向传播**

> **过拟合**

在训练数据上表现的非常良好，但是在测试数据上表现的很差。

> **泛化能力**

模型在未见过的数据上的表现能力。

> **鲁棒性**

模型在面对噪声数据或异常值时的表现能力。

> **正则化**

通过在损失函数中添加额外的惩罚项来防止过拟合。

L1正则化 = $\lambda\sum_{i=1}^{n}|w_i|$

L2正则化 = $\lambda\sum_{i=1}^{n}w_i^2$

> **超参数**

学习率(learning rate): 控制模型参数更新的步长。

正则化参数(regularization parameter): 控制正则化项的强度。

> **Dropout**

在训练过程中随机丢弃一部分神经元，以防止过拟合。

> **卷积神经网络(CNN)**

卷积层(Convolutional Layer): 提取特征

池化层(Pooling Layer): 减少特征图的尺寸，减少计算量

全连接层(Fully Connected Layer): 输出结果

Datasets: 数据集库
{
    load_dataset_builder: 数据集构建器(数据集名称)
    load_dataset: 数据集加载器(数据集名称, 划分名称)
    get_dataset_split_names: 获取数据集的划分名称(数据集名称)
    get_dataset_config_names: 获取数据集的配置名称(数据集名称)
}
pipeline: 用于快速使用预训练模型的接口(API)
Tokenizers: 分词器


