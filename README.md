transE by Python3
=================
所有实体和关系的嵌入按照随机方式进行初始化，算法的每次迭代都要先对实体嵌入向量进行初始化，
然后从训练集中选取一小部分元组作为minibatch的训练元组。对每个这样的元组，取样一个错误
元组，通过一定学习率的梯度更新参数。

训练： transE.py 

测试： test.py

降维：pca.py

数据格式为：head tail relation

THANKS
======
* [Paper](https://www.utc.fr/~bordesan/dokuwiki/_media/en/transe_nips13.pdf) (Bordes et al. 2013)
* [Relation_Extraction](https://github.com/mrlyk423/relation_extraction) by Mrlyk423
