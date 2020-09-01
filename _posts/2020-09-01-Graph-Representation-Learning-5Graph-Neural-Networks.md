---
layout:     post
title:      Graph Representation Learning 图表示学习
subtitle:   Graph Neural Networks
date:       2020-09-01
author:     Aiah
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags:
    - Graph Representation Learning
    - 翻译
---
>Graph Representation Learning是GraphSAGE第一作者William Hamilton的新书，下载地址https://www.cs.mcgill.ca/~wlh/grl_book/files/GRL_Book.pdf

# Graph Neural Networks 图神经网络

>本书第一部分探讨了学习图中节点的低维嵌入的方法，第二部分则重点介绍了更加复杂的编码器模型。

## The Graph Neural Network Model 图神经网络模型

>在本章中，作者看到开发用于图结构数据的复杂编码器的主要挑战在于，通常的深度学习工具并不适用。图神经网络（GNN）作为在图数据上定义深度神经网络的通用框架，作者对其基本内容展开了详细介绍。

## Graph Neural Networks in Practice 实践中的图神经网络

>本章将探索GNN在实践中的应用。具体而言，作者将讨论GNN的一些典型应用以及实践中通常如何实现GNN的优化，其中重点探讨了特别有效的无监督预训练方法。此外，作者还将介绍一些用以正则化和提升GNN效率的常用技术。

## Theoretical Motivations 理论依据

>本章讲述了图神经网络的一些理论依据，旨在向读者介绍不同理论依据背后的核心思想，这样感兴趣的读者就可以自由地探索和结合他们认为合适的直觉知识和动机。