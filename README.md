# AI Image Detective：计算机视觉项目课

这是一套以计算机视觉课程与工程实践为主体的高中 AI 项目教材。仓库主路径保留完整 lesson、notebook、图像素材、训练脚本和部署示例，课堂展示只在首页、目录与少量导读层做整理。

课程主线是：**从感知机、OpenCV、CNN、迁移学习到目标检测与图像检索应用**。学习者最终完成一个“图像侦探”项目：建立图片库，训练或调用视觉模型，完成分类、检索、误判分析和展示。

## 课程主体

| 单元 | 主题 | 主要材料 |
| --- | --- | --- |
| Neural Networks | Perceptron 与神经网络基础 | `lessons/3-NeuralNetworks/03-Perceptron/` |
| Computer Vision 06 | OpenCV 与传统视觉 | `lessons/4-ComputerVision/06-IntroCV/` |
| Computer Vision 07 | CNN 与视觉模型结构 | `lessons/4-ComputerVision/07-ConvNets/` |
| Computer Vision 08 | Transfer Learning | `lessons/4-ComputerVision/08-TransferLearning/` |
| Computer Vision 11 | Object Detection | `lessons/4-ComputerVision/11-ObjectDetection/` |
| CV Recipes | 图像分类工程实践 | `scenarios/classification/` |
| CV Recipes | 目标检测工程实践 | `scenarios/detection/` |
| HTML Demo | 图像相似度应用前端 | `contrib/html_demo/` |

## 高中课堂路径

| 层级 | 学习目标 | 推荐单元 |
| --- | --- | --- |
| 入门课 | 图片、像素、边缘、运动检测 | 06-IntroCV |
| 项目课 | CNN、迁移学习、图像分类 | 07-ConvNets、08-TransferLearning、classification |
| 科创社团 | 目标检测、部署、图像相似度应用 | 11-ObjectDetection、detection、html_demo |

## 互动实验室

[图像检索实验室](https://sherkevin.github.io/ai-image-detective/labs/playground.html) 是本仓库的轻量课堂前端，用来演示特征权重、相似度排序、向量表示和误判分析。正式项目代码、Notebook 与图像素材以 lesson 和 scenarios 目录为准。

## 原始课程与许可

本仓库主体材料来自 Microsoft 官方课程 [AI For Beginners](https://github.com/microsoft/AI-For-Beginners)（MIT License，约 47k stars）的 Computer Vision 单元，并加入 [Computer Vision Recipes](https://github.com/microsoft/computervision-recipes)（MIT License，约 9.8k stars）的分类、检测和 HTML Demo 工程实践。D2L 视觉章节保留在 `source-project/d2l-zh/` 作为深度学习教材参考。许可与来源见 [开源许可与课程资源](LICENSES.md)。

## 阅读方式

在线阅读：[https://sherkevin.github.io/ai-image-detective/](https://sherkevin.github.io/ai-image-detective/)

本仓库采用 Docsify / GitBook 兼容目录组织。`SUMMARY.md` 可供 GitBook 类工具读取，`sidebar.md` 供在线站点使用。
