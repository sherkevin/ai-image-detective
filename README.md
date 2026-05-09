# AI Image Detective：基于 D2L 的高中视觉检索项目教材

> 本教材从高 star 开源教材 [d2l-ai/d2l-zh](https://github.com/d2l-ai/d2l-zh) 改造而来。D2L 是《动手学深度学习》中文版，采用 Apache-2.0 License。本仓库选取其中图像分类、卷积、池化、LeNet、图像增强、微调、目标检测等章节，重排为一条适合高中人工智能课程的视觉项目路线。

## 这本书的主线

本书只围绕一个问题展开：**计算机怎样把一张图片变成可以比较、检索和解释的向量**。

学习者最终会完成一个“图像侦探”项目：给定一张图片，系统在小型图片库中寻找相似图片，解释相似度来自颜色、纹理、边缘还是模型特征，并记录误判案例。课程从像素、特征、距离开始，逐步过渡到卷积神经网络与迁移学习，不把深度学习当成黑箱魔法。

## 上游底座

本仓库保留了 D2L 的关键原始章节，位置为 [`source-project/d2l-zh`](source-project/d2l-zh/README.upstream.md)。

| 来源章节 | 在本书中的作用 |
| --- | --- |
| `image-classification-dataset.md` | 从 Fashion-MNIST 认识数据集、标签与训练/测试划分 |
| `conv-layer.md`、`pooling.md` | 用卷积和池化解释局部特征 |
| `lenet.md` | 读懂一个经典 CNN 的结构 |
| `image-augmentation.md` | 理解数据增强与泛化 |
| `fine-tuning.md` | 把预训练模型迁移到小数据项目 |
| `bounding-box.md`、`kaggle-cifar10.md` | 作为社团拓展：检测、竞赛与完整训练流程 |

## 教材结构

| 编 | 内容 | 产出 |
| --- | --- | --- |
| 第一编：从 D2L 读懂视觉模型 | 数据集、像素、特征、卷积、池化 | 视觉术语卡与模型结构图 |
| 第二编：不用训练模型也能做检索 | 颜色直方图、边缘特征、距离函数 | 浏览器内图像相似检索实验 |
| 第三编：从手工特征到 CNN 特征 | LeNet、数据增强、迁移学习 | 可解释的特征对比报告 |
| 第四编：图像侦探项目 | 小型图片库、检索、误判分析 | 可演示的图像检索 Demo |
| 第五编：科创扩展 | CLIP、多模态、向量数据库 | 社团挑战版项目方案 |

## 互动实验

- [图像检索 Playground](https://sherkevin.github.io/ai-image-detective/labs/playground.html)：浏览器内运行的小型相似度实验，用于观察特征向量、距离和误判。
- [`source-project/d2l-zh/chapters`](source-project/d2l-zh/chapters/)：来自 D2L 的原始章节摘录，供教师备课、进阶阅读和二次改造使用。

## 适用场景

- 高中人工智能校本课程
- 信息科技“人工智能与算法”模块
- 摄影、设计、机器人、工程类科创社团
- 从“图片识别”切入深度学习的项目式课程

## 阅读方式

在线阅读：[https://sherkevin.github.io/ai-image-detective/](https://sherkevin.github.io/ai-image-detective/)

本仓库采用 Docsify / GitBook 兼容目录组织。`SUMMARY.md` 可供 GitBook 类工具读取，`sidebar.md` 供在线站点使用。
