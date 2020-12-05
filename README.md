# Scientific-research-training
该程序采用词袋模型，且根据网上查找的资料以及kaggle中已有的范例进行了改进。

1、采用了TfidfVectorizer中的n-grams模型。在countvectorizer中每个词向量均为一元的，类似not good的短语会被分离为not与good，而good可能会提升该影评的积极程度，导致结果存在偏差。


2、尝试保留停止词，以便更好的生成多元词汇的特征。


3、根据网上的材料，随机森林分类器的效果相对逻辑回归较差，且逻辑回归拥有更快的处理速度，因此在向量化后采用逻辑回归模型进行训练与预测。
