---
layout:     post
title:      Graph Representation Learning 图表示学习
subtitle:   Abstract
date:       2020-09-01
author:     Aiah
header-img: img/post-bg-graph.jpg
catalog: true
tags:
    - Graph Representation Learning
    - 翻译
---
>Graph Representation Learning是GraphSAGE第一作者William Hamilton的新书，下载地址https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf

# Abstract 摘要

从电信网络到量子化学，图结构数据在自然科学和社会科学中无处不在。如果我们希望系统可以从此类数据中学习、推理和推广，则在深度学习框架中建立关系归纳偏差至关重要。近年来，关于图表示学习的研究激增，包括深度图嵌入技术、卷积神经网络对图结构数据的泛化以及受置信传播启发的神经信息传递方法。图表示学习的这些进步促进了许多领域的发展，包括化学合成、3D视觉、推荐系统、问题解答以及社交网络分析等。

该书首先讨论了图表示学习的目标以及图理论和网络分析的主要方法论基础。之后，作者介绍并回顾了学习节点嵌入的方法，包括基于随机游走（random-walk）的方法和知识图谱的应用。

接下来，作者对图神经网络形式（formalism）进行了综合介绍，该形式已经成为使用图数据进行深度学习的主要且快速增长的模型范式。

最后，书中总结了深度生成模型的最新进展，这些模型虽然提出的时间不久，但在图表示学习领域发展迅速。

# 作者介绍

[William Hamilton](https://www.cs.mcgill.ca/~wlh/)于2018年取得斯坦福大学计算机科学博士学位，现为加拿大麦吉尔大学计算机科学助理教授，同时还担任加拿大高等研究院（CIFAR）人工智能主席以及Mila魁北克AI研究所（Mila AI Institute of Quebec）成员。

<img style="display: block; margin: 0 auto; width: 300px" src="https://www.cs.mcgill.ca/~wlh/images/profile_medium.jpg" alt="" />

WIlliam在学生时代取得了诸多荣誉，他曾先后荣获2013年度ACM本科生研究者荣誉提名、2014年度加拿大AI协会（CAIAC）最佳AI主题硕士论文奖，以及2018年度斯坦福大学Arthur Samuel最佳计算机科学博士论文奖。

他的研究兴趣主要是机器学习、网络科学和自然语言处理的结合应用，目前专注于图表示学习领域的快速发展项目。目前他在[Google Scholar](https://scholar.google.com/citations?user=T5tm9eQAAAAJ&hl=en)上的论文总引用量在5000以上。

# 参考
[140页，初学者友好，GraphSAGE第一作者William Hamilton新书《图表示学习》开放下载](https://mp.weixin.qq.com/s/ONBqcge8tghDxiZMmpXqxg)