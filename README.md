# 6_FashionMNIST
2班第6组的机器学习大作业
## 项目结构:
6_FashionMNIST/  
├── data/                  # 数据集存放目录  
│   ├── fashion-mnist_train.csv  # 该文件太大上传失败哦
│   └── fashion-mnist_test.csv  
├── images/                # 可视化结果保存目录  
│   └── ConfusionMatrixes/ # 混淆矩阵保存的文件夹
│   └── ...                # 其他代码中用到的图片  
└── 基于FashionMNIST数据集的分类.ipynb        # notebook文件 

## 环境要求
Python 3.8+  
依赖库：
pandas==1.5.3  
numpy==1.23.5  
matplotlib==3.7.1  
scikit-learn==1.2.2  
seaborn==0.12.2  
torch==2.0.0  

## 模型实现
本项目实现了 8 种分类模型，涵盖传统机器学习与深度学习：
传统机器学习模型：
    
    随机森林（RandomForest）
    逻辑回归（LogisticRegression）
    支持向量机（SVC）
    决策树（DecisionTree）
    多层感知机（MLP）
    K 近邻（KNC）
集成学习模型：
    
    投票法（Voting Classifier）
深度学习模型：
    
    卷积神经网络（CNN，基于 PyTorch）
