## 1、环境

安装requirements.txt中的依赖库

```
pip install requirements.txt
```

## 2、模型训练

运行训练文件

```
train.ipynb
```

默认参数

```
batch_size 64
epoch 20
optimizer SGD
learning rate 0.1
```

在modelpth文件夹中得到多个权重，可选择准确率Accuracy最高的对应的权重

## 3、模型测试

运行测试文件

```
test.ipynb
```

载入最佳模型，在测试集进行分类

### 4、对比模型

运行对比模型文件

```
DecisionTree SVM KNN.ipynb
```

有三种算法：决策树、支持向量机、K近邻
