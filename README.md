# Kaggle-Dogs-vs-Cats链接：
- https://www.kaggle.com/competitions/dogs-vs-cats-redux-kernels-edition
# 实现方法 
- tensorflow 2.0 
- transfer learning
# 最终最好成绩
- ![0.03694](https://github.com/su-xiaoman/Tensorflow-For-Kaggle-Dogs-vs-Cats/blob/main/best_result.png)
- [对应jupyter notebook](https://github.com/su-xiaoman/Tensorflow-For-Kaggle-Dogs-vs-Cats/blob/main/kaggle-dogs-vs-cats_current_best.ipynb)
# 深度学习在不同质量的特征向量下的最好成绩
- 0.03065 vs 0.03694（均已上传）

# 更新1
- 加入了传统的xgboost和logistic回归等机器学习方法
- 低于0.03的成绩基本上完完全全由机器学习所取得，这表明在小样本条件下，机器学习往往能够取得比深度学习更好的效果
- 最好成绩 ![0.02983](https://github.com/su-xiaoman/Tensorflow-For-Kaggle-Dogs-vs-Cats/blob/main/加上机器学习.png)
- 参考kaggle大佬：[链接](https://www.kaggle.com/datasets?search=cats-and-dogs-embedded-data)
- [对应jupyter notebook](https://github.com/su-xiaoman/Tensorflow-For-Kaggle-Dogs-vs-Cats/blob/main/kaggle-cats-vs-dogs-with_comment_version.ipynb) 

# 更新2
-  加入了.gitignore
-  合并了tensorflow版本和机器学习版本
-  加入了在更高质量的特征向量上的tensorflow训练结果图片

# 更新3
- 为tensorflow版本提供了更多关于特征向量提取的说明和链接
- 为两种方式都加入了html以全球在不打开jupyter notebook/lab的情况下，也可以直接查看
- 没有为传统机器学习版本提供更多的说明，但是加入了集成学习模块sklearn.ensemble.VotingClassifier。由于相对于手动比例赋值，实验效果不佳，因此没有进一步讨论。
