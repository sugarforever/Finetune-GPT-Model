# 如何微调OpenAI的模型

## [openai_finetune.ipynb](openai_finetune.ipynb)

该notebook将演示如何实现基于OpenAI模型的微调。我们将使用一组小型数据集，其中包含一些网络用语，比如关于涉及“六”的赞扬词句，以及其他中性语句。我们将使用这些数据来训练模型，以便它可以对输入文本实现情绪分类(positive, neutral)。

注意，本数据集并没有采集对应情绪分类negative的数据，因此我们将不会对此进行训练。

