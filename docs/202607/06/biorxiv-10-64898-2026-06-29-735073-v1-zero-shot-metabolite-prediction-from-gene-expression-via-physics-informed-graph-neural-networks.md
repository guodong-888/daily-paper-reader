---
title: Zero-Shot Metabolite Prediction from Gene Expression via Physics-Informed Graph Neural Networks
title_zh: 基于物理信息图神经网络的基因表达零样本代谢物预测
authors: "Novella Rausell, C., Rabelink, T., Mahfouz, A."
date: 2026-07-02
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.29.735073v1.full.pdf"
tags: ["query:flap-ex-met"]
score: 6.0
evidence: 提供从基因表达预测代谢物浓度的方法，可用于研究运动与皮瓣存活中的代谢变化
tldr: "从基因表达预测代谢物浓度是连接调控程序与代谢表型的关键。现有方法依赖静态酶-代谢物映射，难以泛化到新代谢物。本文提出GAZE，一种物理信息图神经网络，整合酶表达、EC功能嵌入和ChemBERTa代谢物描述符，通过代谢物条件阅读器实现零样本预测。在标准交叉验证中R²=0.816；留一代谢物零样本预测中，物理信息变体将中位R²差距从-0.72减半至-0.34，30%未见过代谢物获正R²；外部验证中位斯皮尔曼ρ=0.330。GAZE显著优于现有方法，为零样本代谢物预测提供了有效框架。"
source: biorxiv
selection_source: fresh_fetch
motivation: 现有方法依赖静态酶-代谢物映射，缺乏泛化能力，无法预测未见过代谢物。
method: GAZE使用物理信息图神经网络，整合酶表达、EC嵌入和SMILES描述符，通过代谢物条件阅读器实现零样本预测。
result: "标准交叉验证R²=0.816；零样本场景中位R²差距减半，30%未见过代谢物正R²；外部验证中位斯皮尔曼ρ=0.330。"
conclusion: GAZE有效实现零样本代谢物预测，为连接基因表达与代谢表型提供强大工具。
---

## 摘要
从基因表达预测代谢物浓度对于将调控程序与代谢表型联系起来至关重要。先前的方法依赖于静态的酶-代谢物映射，通常忽略数据驱动学习或生化约束，限制了其泛化到新代谢物的能力。我们提出了GAZE（零样本代谢物估计的图注意力网络），这是一种物理信息图神经网络，它将酶表达、酶委员会功能嵌入和ChemBERTa代谢物描述符整合到一个统一的代谢图（5,414个节点，16,307条边）中。代谢物条件读取器使用每个代谢物的SMILES嵌入来查询学习到的通路表示，实现零样本预测，无需特定于代谢物的参数。我们在三种场景下评估GAZE：（i）在癌症代谢谱图集（18,044个基因，180种代谢物，867个细胞系）上进行标准交叉验证，达到R²=0.816；（ii）在50种保留代谢物上进行留一代谢物（LOMO）零样本评估，物理信息变体将中位R²赤字相对于标准GNN基线减半（-0.34 vs -0.72），其中30%未见代谢物获得正R²；（iii）在独立透明细胞肾细胞癌组织队列（220个样本）上进行外部验证，GAZE无需微调即可在214种代谢物上实现中位Spearman ρ=0.330。GAZE在所有评估设置中均优于scCellFie、MEBOCOST和UnitedMet。

## Abstract
Predicting metabolite concentrations from gene expression is instrumental for linking regulatory programs to metabolic phenotypes. Prior approaches rely on static enzyme-metabolite mappings and often omit data-driven learning or biochemical constraints, limiting their ability to generalize to new metabolites. We present GAZE (Graph Attention for Zero-shot metabolite Estimation), a physics-informed graph neural network that integrates enzyme expression, Enzyme Commission functional embeddings, and ChemBERTa metabolite descriptors within a unified metabolic graph (5,414 nodes, 16,307 edges). A Metabolite-Conditioned Reader uses each metabolites SMILES embedding to query learned pathway representations, enabling zero-shot prediction with no metabolite-specific parameters. We evaluate GAZE in three scenarios: (i) standard cross-validation on the Cancer Atlas of Metabolic Profiles (18,044 genes, 180 metabolites, 867 cell lines), achieving R2 = 0.816; (ii) leave-one-metabolite-out (LOMO) zero-shot evaluation across 50 held-out metabolites, where the physics-informed variant halves the median R2 deficit relative to a standard GNN baseline (-0.34 vs. -0.72), with 30% of unseen metabolites achieving positive R2; and (iii) external validation on an independent clear cell renal cell carcinoma tissue cohort (220 samples), where GAZE achieves median Spearman{rho} = 0.330 across 214 metabolites without fine-tuning. GAZE outperforms scCellFie, MEBOCOST, and UnitedMet across all evaluation settings.