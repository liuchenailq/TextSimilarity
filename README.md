# TextSimilarity
CCF竞赛 “技术需求”与“技术成果”项目之间关联度计算模型 baseline 0.68541449

## 运行环境
直接放在kaggle notebook上运行即可

## 方法
句子的词向量平均作为句子的向量特征  
技术需求的title和技术成果的title向量做相减、相乘作为特征传入全连接层


