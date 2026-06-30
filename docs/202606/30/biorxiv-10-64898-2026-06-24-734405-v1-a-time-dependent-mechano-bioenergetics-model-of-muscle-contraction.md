---
title: A time-dependent mechano-bioenergetics model of muscle contraction
title_zh: 肌肉收缩的时间依赖性机械生物能量学模型
authors: "Konno, R. N., Lichtwark, G. A., Dick, T. J. M."
date: 2026-06-30
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.24.734405v1.full.pdf"
tags: ["query:flap-ex-met"]
score: 6.0
evidence: 肌肉收缩的时间依赖性机械-生物能量学模型；可用于研究运动诱导的代谢变化
tldr: 现有骨骼肌能量消耗模型忽略时间依赖性和ATP恢复成本，难以预测重复收缩的能量响应。本研究基于Ca2+运输、横桥循环和ATP再生等生理过程，构建了时间依赖性模型。模型成功预测了动态、次最大和抽搐收缩下的能量率，并再现了收缩频率对峰值能量率的影响及恢复时间过程。该模型参数少、计算成本低，可泛化至不同肌肉和物种，便于整合到肌肉骨骼模型中。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有模型未考虑能量消耗的时间依赖性和ATP恢复成本，限制了重复收缩任务的预测能力。
method: 构建包含Ca2+运输、横桥循环和ATP再生的时间依赖性机械-生物能量学模型，参数来自实验数据。
result: 模型准确预测了动态、次最大和抽搐收缩下的能量率，捕捉收缩频率和恢复时间过程。
conclusion: 模型参数少、计算成本低，可推广至不同肌肉和物种，适用于多尺度肌肉骨骼建模。
---

## 摘要
预测骨骼肌在不同收缩条件下的能量消耗对于理解运动至关重要。现有数学模型虽然捕捉了耗能过程的机械依赖性，但忽略了与ATP再生相关的时间依赖行为和恢复成本。这种时间依赖性对于预测肌肉在重复性或周期性任务（如运动）中的能量响应非常重要，因为肌肉会经历多次收缩循环。本研究提出了一种基于生理过程（Ca2+运输成本、横桥循环成本和ATP再生）预测能量速率的新模型。以前的数学模型包括对Ca2+运输和横桥循环的依赖性，但忽略了收缩后的时间依赖响应和后续的ATP恢复。模型参数来自现有离体肌肉制备数据，并在包括动态、次最大和单次收缩等一系列收缩条件下的独立数据集上验证了预测的能量速率。时间依赖模型能够捕捉收缩频率对峰值能量速率的影响以及实验观察到的能量恢复的时间过程。该模型在保持自由参数数量最少和计算成本低的情况下，捕捉了关键的生理过程。这使其能够跨肌肉和物种推广，并实现到更大规模的肌肉骨骼模型中。

## Abstract
Predictions of skeletal muscle energy consumption under a diverse range of muscle contractile conditions are critical for improving our understanding of locomotion. Existing mathematical models, while capturing the mechanical dependence of energy consuming processes, neglect the time-dependent behaviour and recovery costs associated with regenerating ATP. This time-dependence is important for predicting the energetic response of muscles during repetitive or cyclical tasks like locomotion, where muscle undergoes many contraction cycles. This study presents a novel model to predict energetic rates based on physiological processes: Ca2+ transport costs, cross-bridge cycling costs, and ATP regeneration. Previous mathematical models include the dependence on Ca2+ transport and cross-bridge cycling, but neglect the time-dependent response and the subsequent recovery of ATP following the contraction. Model parameters were obtained from existing data on isolated muscle preparations, and predicted energetic rates were validated on separate datasets across a range of contractile conditions including dynamic, sub-maximal, and twitch contractions. The time-dependent model was able to capture the influence of contraction frequency on peak energetic rates and the time-course of energetic recovery observed experimentally. The model captures key physiological processes while maintaining a minimal number of free parameters and low computational cost. This enables generalisability across muscles and species, and implementation into larger scale musculoskeletal models.