# TextSimilarity
CCF竞赛 “技术需求”与“技术成果”项目之间关联度计算模型 baseline 0.68541449

## 使用方法
本地运行preprocess文件，生成词汇表、训练集、测试集、词向量文件   
在kaggle notebook上运行CCF_WordSolution文件

## 模型方法
句子的词向量平均作为句子的向量特征  
向量做点乘作为特征传入全连接层

