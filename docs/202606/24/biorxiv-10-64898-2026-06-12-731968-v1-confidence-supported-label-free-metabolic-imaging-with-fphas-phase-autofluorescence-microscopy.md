---
title: Confidence-supported label-free metabolic imaging with FPhaS phase autofluorescence microscopy
title_zh: 基于FPhaS相位自发荧光显微镜的置信度支持的无标记代谢成像
authors: "Fan, H., Shi, J., Yang, Z., Ho, A., Yang, L., Tan, K. K. D., Aksamitiene, E., Boppart, S. A."
date: 2026-06-17
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.12.731968v1.full.pdf"
tags: ["query:flap-ex-met"]
score: 6.0
evidence: 无标记代谢成像方法，可用于研究运动期间皮瓣代谢变化
tldr: 传统光学氧化还原比缺乏光子支持和细胞背景信息。FPhaS框架通过集成定量相位成像与自荧光多谐波显微镜，利用统一校准实现结构-代谢共定位。在A549细胞高低光子条件下验证，仅当光子支持和结构标准均满足时，置信加权比值与寿命测量一致性改善。该方法重新定义了标签自由代谢成像，聚焦于有光学证据支持定量推断的区域。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统光学氧化还原比缺乏光子支持和细胞背景信息，无法进行定量聚合。
method: 提出FPhaS框架，集成QPI与SLAM，通过统一非生物校准对齐，分解为细胞存在、比率可信度和置信支持池化。
result: 在A549细胞高低光子条件下，仅当分母光子支持和结构标准同时满足时，置信加权比值与寿命测量一致性改善。
conclusion: FPhaS将代谢成像从全面比率图转变为识别有光学证据支持定量推断的区域。
---

## 摘要
无标记光学氧化还原成像利用内源性NAD(P)H和FAD自发荧光评估活体标本的代谢。传统光学氧化还原比将这两个通道合并为一个单一值，但无法指示像素是否具有足够的光子支持或定量聚合所需的细胞背景。为解决这一局限，我们引入FPhaS，一种固定校准的相位-自发荧光框架，将定量相位成像（QPI）与同时无标记自发荧光多谐波显微镜（SLAM）相结合，仅使用荧光寿命成像（FLIM）进行验证。由于QPI和SLAM使用同一物镜采集，统一的非生物校准将相位导出的结构数据与自发荧光帧对齐，产生0.39像素的残差。该校准在所有生物标本中保持一致。这一共享几何参考可实现局部结构和代谢信息的评估，而非比较近似对齐的图像。FPhaS将数据分解为细胞存在、比率可信度和置信度支持池化。我们在高、低光子条件下对A549细胞验证了FPhaS；该框架设计为可推广至其他细胞和组织类型。在掩模锁定的细胞区域内，将置信度加权强度氧化还原估计与寿命导出的测量进行比较。仅当分母光子支持和独立结构标准同时满足时，一致性才得到改善。同一参考层生成了代谢含量、代谢-结构组织以及测量可靠性的细胞水平描述符，同时在荧光采集减少的情况下约束CombinedWLS重建。FPhaS重新定义了无标记代谢成像，从生成全面比率图转变为识别光学证据支持定量推断的区域。

## Abstract
Label-free optical redox imaging utilizes endogenous NAD(P)H and FAD autofluorescence to evaluate metabolism in living specimens. The conventional optical redox ratio collapses these two channels into a single value; however, it does not indicate whether a pixel has sufficient photon support or the cellular context necessary for quantitative aggregation. To address this limitation, we introduce FPhaS, a fixed-calibration phase- autofluorescence framework that integrates quantitative phase imaging (QPI) with simultaneous label-free autofluorescence multi-harmonic microscopy (SLAM), using fluorescence lifetime imaging (FLIM) solely for validation. Because QPI and SLAM are acquired with the same objective, a unified non-biological calibration aligns phase-derived structural data with the autofluorescence frame, yielding a residual error of 0.39 pixels. This calibration is maintained across all biological specimens. This shared geometric reference enables local evaluation of structural and metabolic information, rather than comparing approximately aligned images. FPhaS decomposes the data into cell presence, ratio credibility, and confidence-supported pooling. We validated FPhaS on A549 cells under high and low-photon conditions; the framework is designed to generalize to other cell and tissue types. Confidence-weighted intensity redox estimates were compared with lifetime-derived measurements within mask-locked cellular regions. Concordance improved exclusively when both the denominator photon support and an independent structural criterion were satisfied. The same reference layer generated cell-level descriptors of metabolic content, metabolic-structural organization, and measurement reliability, while also constraining the CombinedWLS reconstruction under diminished fluorescence acquisition. FPhaS redefines label-free metabolic imaging from producing comprehensive ratio maps to identifying regions where optical evidence substantiates quantitative inference.