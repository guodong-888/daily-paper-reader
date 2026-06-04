---
title: Wide-Field Calcium and Flavoprotein Autofluorescence Imaging in Living Mice
title_zh: 活体小鼠的宽场钙和黄素蛋白自发荧光成像
authors: "Yoshida, T."
date: 2026-05-27
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.14.725112v2.full.pdf"
tags: ["query:flap-ex-met"]
score: 6.0
evidence: 宽场黄素蛋白自发荧光成像可反映线粒体氧化还原动态，可用于研究运动诱导的皮瓣代谢变化
tldr: 宽场成像技术通过完整颅骨同时采集GCaMP钙信号和黄素蛋白自发荧光，实现小鼠皮层活动的长期纵向监测。该方法包含系统的动物准备、设备组装与MATLAB数据分析流程，采用ΔF/F校正、参考信号校正和伪影去除，结合图谱配准与ROI分析。实验证明该方案能够稳定获取神经元群体活动和代谢动态，成本低、可重复性强，为皮层生理与神经疾病研究提供了实用工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 为克服传统成像局限，开发一种可重复、低成本的宽场方法，实现小鼠皮层活动长期纵向监测。
method: 采用GCaMP与黄素蛋白自发荧光，通过完整颅骨进行宽场成像，执行ΔF/F归一化、信号校正、伪影去除、图谱配准及ROI分析。
result: 成功获取皮层神经元活动和代谢动态信号，支持多时间点重复测量，数据分析流程有效提取ROI数据。
conclusion: 该宽场成像方案简单可靠，适用于小鼠皮层生理与神经系统疾病模型的纵向研究。
---

## 摘要
宽场成像（WFI）是一种介观方法，用于监测皮层范围的活动，具有高时间分辨率和宽视野。由于其简单的光学配置和对慢性实验制剂的兼容性，WFI已成为系统神经科学和疾病模型研究中的重要工具。在本章中，我们描述了在小鼠中进行慢性经颅WFI的实用方案，使用两种互补的光学信号：基因编码的钙指示剂（GCaMP）和内源性黄素蛋白自发荧光。钙成像提供了神经元群体活动的可靠读数，而黄素蛋白成像反映了线粒体氧化还原动力学和细胞代谢需求。我们详细介绍了动物准备、颅骨清理、头板植入、宏观镜组装、同步感觉刺激、触发图像采集以及基于MATLAB的数据分析的程序。分析工作流程包括ΔF/F归一化、基于参考的信号校正和伪影减少，然后进行试次平均、图谱配准和感兴趣区域分析。由于成像通过完整的颅骨进行，该方案能够在同一动物中进行长时间的重复纵向测量。这种方法可重复、成本效益高，并适用于皮层生理学和神经系统疾病的研究。

## Abstract
Wide-field imaging (WFI) is a mesoscopic approach for monitoring cortex-wide activity with high temporal resolution and a broad field of view. Owing to its simple optical configuration and compatibility with chronic preparations, WFI has become an important tool in systems neuroscience and disease-model research. In this chapter, we describe practical protocols for chronic transcranial WFI in mice using two complementary optical signals: genetically encoded calcium indicators (GCaMP) and endogenous flavoprotein autofluorescence. Calcium imaging provides a robust readout of neuronal population activity, whereas flavoprotein imaging reflects mitochondrial redox dynamics and cellular metabolic demand. We detail procedures for animal preparation, skull clearing, headplate implantation, macroscope assembly, synchronized sensory stimulation, triggered image acquisition, and MATLAB-based data analysis. The analysis workflow includes {Delta}F/F normalization, reference-based signal correction, and artifact reduction, followed by trial averaging, atlas registration, and region-of-interest analysis. Because imaging is performed through the intact skull, the protocol enables repeated longitudinal measurements in the same animal over extended periods. This approach is reproducible, cost-effective, and adaptable to studies of cortical physiology and neurological disorders.