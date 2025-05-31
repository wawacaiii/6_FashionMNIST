# 6_FashionMNIST
2班第6组的机器学习大作业
## 项目结构:
6_FashionMNIST/
├── data/                  # 数据集存放目录
│   ├── fashion-mnist_train.csv
│   └── fashion-mnist_test.csv
├── images/                # 可视化结果保存目录
│   └── ConfusionMatrixes/
├── models/                # 训练好的模型保存目录
├── src/                   # 源代码目录
│   ├── data_processing.py # 数据处理模块
│   ├── model_training.py  # 模型训练模块
│   ├── model_evaluation.py# 模型评估模块
│   └── visualization.py   # 可视化模块
├── utils/                 # 工具函数
├── requirements.txt       # 环境依赖
└── main.py                # 主程序入口
## 环境要求
Python 3.8+
依赖库：
text
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
