---
layout: post
title:  深度学习（四十二）——行人重识别, 人脸检测/识别进阶
category: DL 
---

# 行人重识别

行人重识别（Person re-identification）也称行人再识别，是利用计算机视觉技术判断图像或者视频序列中是否存在特定行人的技术。广泛被认为是一个图像检索的子问题。给定一个监控行人图像，检索跨设备下的该行人图像。旨在弥补目前固定的摄像头的视觉局限，并可与行人检测/行人跟踪技术相结合，可广泛应用于智能视频监控、智能安保等领域。

参考：

https://github.com/gjy3035/Awesome-Crowd-Counting

人群计数最全代码、数据、论文合集

https://mp.weixin.qq.com/s/ZmX_ir1pSUZbCaFpbcQ6Lw

一文读懂行人检测算法

https://zhuanlan.zhihu.com/p/26168232

行人重识别：从哈利波特地图说起

https://zhuanlan.zhihu.com/p/50387521

从零开始行人重识别

https://mp.weixin.qq.com/s/_NDw7pFmDB07mliHTA6VYQ

旷视行人再识别（ReID）突破

https://zhuanlan.zhihu.com/p/31181247

从人脸识别到行人重识别，下一个风口

https://mp.weixin.qq.com/s/zRdJktyk1LZWUd2cyTjpiw

基于图像检索的行人重识别

https://zhuanlan.zhihu.com/p/31473785

行人再识别中的迁移学习：图像风格转换

https://mp.weixin.qq.com/s/fX94rPgNHrOaQTqBv-ZADg

基于视频的行人再识别新进展：区域质量估计方法和高质量的数据集

https://mp.weixin.qq.com/s/rf-pGfkQFK3abkOLEEVOeA

PTGAN：针对行人重识别的生成对抗网络

https://zhuanlan.zhihu.com/p/34778414

基于时空模型无监督迁移学习的行人重识别

https://zhuanlan.zhihu.com/p/35296881

刷新三数据集纪录的跨镜追踪(行人再识别-ReID)技术介绍

https://mp.weixin.qq.com/s/ZbmJGO3lqwNM2z-E4_Mpbw

由“刷脸”到“识人”，云从科技刷新跨镜追踪(ReID)技术三项世界纪录！

https://zhuanlan.zhihu.com/p/38603624

云从科技资深算法研究员：详解跨镜追踪(ReID)技术实现及难点

https://mp.weixin.qq.com/s/leuILzYz40PqrwsCatYhPw

行人再识别年度进展

https://zhuanlan.zhihu.com/p/37931822

你需要知道的10种行人属性

https://mp.weixin.qq.com/s/YBorhQrJ0UL3HZQHgd5D6A

清华等机构提出基于内部一致性的行人检索方法，实现当前最优

https://zhuanlan.zhihu.com/p/40514536

一个强力的ReID basemodel

https://mp.weixin.qq.com/s/mktVMZ0Fdo0mubstpl2GDA

Repulsion loss：专注于遮挡情况下的行人检测

https://mp.weixin.qq.com/s/LZCYx-VyOAMWXBS76ttkFw

如何在不同摄像头里识别行人？多层相似度感知CNN网络解析

https://mp.weixin.qq.com/s/iUPZ4DfL65_NV2v3eWomww

无监督深度关联学习大幅提高行人重识别性能

https://mp.weixin.qq.com/s/Wj6RBS7gYd9skE3AU1s4Qg

尺度不变提升人群计数性能

https://mp.weixin.qq.com/s/3eLL5Xg2mBFWnbYFbW486A

行人检测全新视角：从人体中轴线标注出发

https://mp.weixin.qq.com/s/VwejfjxjVnGFW3WXXyL1og

ALFNet：向高效行人检测迈进

https://mp.weixin.qq.com/s/3gzlln0yqqXQ6Xbwt-VXjw

OR-CNN行人检测：为‘遮挡’而生

https://mp.weixin.qq.com/s/yrygkZUwsCL-twTFvA--1w

尺度不变网络提升人群计数性能

https://mp.weixin.qq.com/s/K7JNqjuUfotTODtJU1W-YQ

快速精准的人头检测，代码已开源

https://mp.weixin.qq.com/s/DZmAWpptAVIqA_7L24ldHg

行人重识别PCB-RPP，SGGNN

https://mp.weixin.qq.com/s/e_n-BsPkrPd4MsyvlMVeYg

行人重识别告别辅助姿势信息，商汤、中科大提出姿势无关的特征提取GAN

https://mp.weixin.qq.com/s/l8ExvxOERUngHBqtep-ZWw

人群计数（Crowd Counting）研究综述

https://zhuanlan.zhihu.com/p/51511683

Graph Reid系列结合谱聚类做特征变换

https://zhuanlan.zhihu.com/p/47073533

结合时空的Re-ID系列：ECCV2018 TAUDL

https://mp.weixin.qq.com/s/eKHL0F3tnjEHY10d5PqkMg

最新Video-based ReID论文核心解读

https://mp.weixin.qq.com/s/iotqiyRrH4kwWmBvYi-tMQ

中科院&地平线开源state-of-the-art行人重识别算法EANet:增强跨域行人重识别中的部件对齐

https://zhuanlan.zhihu.com/p/54576174

行人重识别新任务：训练只需一张标注图片

https://zhuanlan.zhihu.com/p/52274204

AAAI2019 Spatial-Temporal Person Re-identification

https://zhuanlan.zhihu.com/p/55320029

行人跨模态重识别：双向限制的排序损失

https://zhuanlan.zhihu.com/p/55787893

亚马逊提出：用于人群计数的尺度感知注意力网络

https://mp.weixin.qq.com/s/U-ICoZQWatyJmkPcnXNRbA

最新最简易的迁移学习方法，人员再识别新模型

https://mp.weixin.qq.com/s/ajpxP3b5nw2AC393uBypvA

西工大开源拥挤人群数据集生成工具，大幅提升算法精度

https://mp.weixin.qq.com/s/BDgIf6foDGtCNc48JPqrcg

行人重识别算法优化技巧：Bags of Tricks and A Strong Baseline

# 人脸检测/识别进阶

https://mp.weixin.qq.com/s/-G94Mj-8972i2HtEcIZDpA

人脸识别世界杯榜单出炉，微软百万名人识别竞赛冠军分享

https://mp.weixin.qq.com/s/bqWle_188lhYO4hpCfafkQ

用浏览器做人脸检测，竟然这么简单？

https://mp.weixin.qq.com/s/kn9JS55wIW2cfpUv7Jm0eQ

深度学习教你如何“以貌取人”！

https://mp.weixin.qq.com/s/3xEDtMoe0iRQSZiN5A1FGw

IPHONE X“刷脸”技术奥秘大揭底

https://mp.weixin.qq.com/s/s5HL6y2P9_KqpSAQg08URw

世界最大人脸对齐数据集ICCV 2017：距离解决人脸对齐已不远

https://mp.weixin.qq.com/s/7AnF0uMgepchiUeqfqVbCg

清华大学王生进：新智能安防：人脸识别技术与应用系统

https://mp.weixin.qq.com/s/-T5k2ViPjvEoXccKt-_J3Q

中科院自动化研究所提出FaceBoxes：实时、高准确率的CPU面部检测器

https://www.leiphone.com/news/201707/mFuwXGvZBhoVQD5S.html

一秒分辨出杨臣刚、王大治和孙楠，这个黑产居然用AI来"打码"

https://mp.weixin.qq.com/s/PF7_kSnwngnJ1jeh7ebyww

手把手教你用1行代码实现人脸识别

http://blog.csdn.net/gitchat/article/details/78546894

TensorFlow人脸识别网络与对抗网络搭建

https://mp.weixin.qq.com/s/YRsVi09u3W0aQMdsR5KY4Q

腾讯AI Lab提出Face R-FCN与Face CNN，刷新人脸检测与识别两大测评记录

https://mp.weixin.qq.com/s/zyMIRGig-m732rvraPKxwA

单样本学习：使用孪生神经网络进行人脸识别

https://mp.weixin.qq.com/s/QJm7YoCYmiF0dX8uac5w4Q

旷视研究院：被遮挡人脸区域检测的技术细节

https://mp.weixin.qq.com/s/Fmi9RJz-bMOYBoZWt1nWag

人脸注意机制网络

https://mp.weixin.qq.com/s/s9H_OXX-CCakrTAQUFDm8g

申省梅颜水成团队获国际非受限人脸识别竞赛IJB-A冠军，主要负责人熊霖技术分享

https://mp.weixin.qq.com/s/ZFFSTFDVxFUe2KOFy8XDxw

人脸识别——新的一个境界（无约束）

https://mp.weixin.qq.com/s/GlS2VJdX7Y_nfBOEnUt2NQ

使用Siamese神经网络进行人脸识别

https://mp.weixin.qq.com/s/xDEga2tITO8rVkvXCZ62sg

中国团以98%精度夺得MegaFace人脸识别冠军

https://mp.weixin.qq.com/s/HVooLtr_k6fwh2N3GjMb1A

新研究提出深度残差等价映射：由正脸加强侧脸识别效果

https://mp.weixin.qq.com/s/9noWOZJSRAi424ZDTD1IRQ

世界权威评测冠军：百度人脸检测算法PyramidBox

https://www.zhihu.com/question/37060782

人脸识别哪家强？不如问哪家公司吹牛逼强

https://mp.weixin.qq.com/s/S_T0tYhZ1pjoIMysP0aVWA

美军AI黑科技：黑暗中也能准确识别人脸，谁该为此感到紧张？

https://mp.weixin.qq.com/s/GLKvzC_o6MR1ixThAVc9lQ

CosFace: 面向深度人脸识别的增强边缘余弦损失函数设计

https://mp.weixin.qq.com/s/AMDkkbdTQbL-2jyweVid-A

摆好Pose却没管理好面部表情？腾讯优图Facelet-Bank人脸处理技术了解一下

https://mp.weixin.qq.com/s/OjId_YfxkhEh4tJ1Sw-Hbw

多伦多大学反人脸识别，身份欺骗成功率达99.5%

https://mp.weixin.qq.com/s/tUSNk5R_zbEFz-yIx0LXYQ

基于DNN的人脸识别中的反欺骗机制

https://mp.weixin.qq.com/s/mjdW7xY77H03RIKuKuFmQg

人脸画像合成研究的综述与对比分析

https://mp.weixin.qq.com/s/Ieha-lJ_KuEnpbJha_nxJw

利用人脸图片准确识别年龄：上海大学研究者提出“深度回归森林”

https://mp.weixin.qq.com/s/9VTpbqwALmxr07pEfdQBCA

旷视科技提出GridFace：通过学习局部单应变换实现人脸校正

https://mp.weixin.qq.com/s/z726pDBhn5bML5Xho2XCig

人脸对齐与跟踪如何克服遮挡、姿态变化带来的特征点跳变？

https://mp.weixin.qq.com/s/qpP6AzLdgtH6NnIUl4JNpQ

腾讯AI Lab提出正交深度特征分解算法：在多个跨年龄人脸识别任务中创造新记录

https://mp.weixin.qq.com/s/J4_snLK7DoV5oN7GP5M_Ww

新思路！商汤开源利用无标注数据大幅提高精度的人脸识别算法

https://mp.weixin.qq.com/s/4xYAhNys6svltEb4cQUrXw

Bi-box行人检测：‘行人遮挡’为几何？

https://mp.weixin.qq.com/s/IfZ5gTZrSFqQP2cpcIxAeQ

清华&商汤开源CVPR2018超高精度人脸对齐算法LAB

https://mp.weixin.qq.com/s/R1hdkPTdFCo7JvOKNcEzJg

DeepMind&VGG提出基于集合的人脸识别算法GhostVLAD,精度远超IJB-B数据集state-of-the-art

https://mp.weixin.qq.com/s/CH46uvOshGss7O2bbxFoWQ

曹杰：Rotating is Believing

https://mp.weixin.qq.com/s/unoSZVPQrjMjjxSbnp1IBQ

FaceBoxes—官方开源CPU实时高精度人脸检测器

https://zhuanlan.zhihu.com/p/55983565

中科院和京东AI研究院提出：改进SRN人脸检测算法，目前业界最强！

https://mp.weixin.qq.com/s/KY11jsedOa0HHIhET83V3g

目前最强性能的人脸检测算法Improved SRN

https://mp.weixin.qq.com/s/Chw_gLxQHdfe0hFJGMk-3A

日本东北大学改进单阶段人脸检测—兼具速度与精度优势

https://mp.weixin.qq.com/s/E9Esoe4VHvMdJNTbxF-sXA

ShapeNet:超实时人脸特征点检测与形状拟合开源库

https://mp.weixin.qq.com/s/pmnb_WnncL12T1IZoso5DA

DeepID

https://mp.weixin.qq.com/s/BV3xv8mH6K7dV1nik0X5aw

PFLD：简单、快速、超高精度人脸特征点检测算法

https://mp.weixin.qq.com/s/kH3-WUX4rc2SaLJcGzVLcQ

如何检测极小人脸？试试超分辨率

https://github.com/ShiqiYu/libfacedetection

libfacedetection算法开源

https://mp.weixin.qq.com/s/-VknGwKKY14cT-lZ7sC43A

人脸识别--基于深度学习以人类为中心的图像理解

https://mp.weixin.qq.com/s/bAlaCWg4OEprpoZqQFQg1w

百度提出PyramidBox人脸检测算法

https://mp.weixin.qq.com/s/CYZvFb7kryE-8HV3teGRzA

有效遮挡检测的鲁棒人脸识别
