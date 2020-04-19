# Chinese-movie-comments-sentiment-analysis-pytorch
中文电影评论情感分类，pytorch实现Text-CNN。

数据集包括：
1. 训练集。包含2W条左右中文电影评论，其中正负向评论各1W条左右。
2. 验证集。包含6K条左右中文电影评论，其中正负向评论各3K条左右。
3. 测试集。包含360条左右中文电影评论，其中正负向评论各180条左右。
4. 预训练词向量。中文维基百科词向量word2vec。

预训练词向量的下载：
- 链接：https://pan.baidu.com/s/1887bRjGQU2vm-4Re_C4ELw 
- 提取码：lhn4

使用Text-CNN模型，模型包括词嵌入层、卷积层、池化层和全连接层。

![](https://pic.downk.cc/item/5e9bc837c2a9a83be5a96d95.jpg)
