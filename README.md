﻿# 实现说明
基于pytorch和bert，参考NER的网络结构，第一个全连接的输出层输出属性/观点的起始位置（按照BEIS，共有8个类），第二个输出观点+属性的分类（合计有28个类）

# 运行环境
python3.6 + pytorch==1.0.1 + pytorch-pretrained-bert==0.6.2

# 运行结果