---
title: A time-dependent mechano-bioenergetics model of muscle contraction
title_zh: 肌肉收缩的时间依赖性力学-生物能量学模型
authors: "Konno, R. N., Lichtwark, G. A., Dick, T. J. M."
date: 2026-06-30
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.24.734405v1.full.pdf"
tags: ["query:flap-ex-met"]
score: 6.0
evidence: 肌肉收缩的时间依赖机械-生物能量学模型；运动期间的ATP再生和代谢
tldr: 现有肌肉能量消耗模型忽略了时间依赖性和ATP再生恢复成本，难以预测循环收缩的代谢反应。本研究提出一个基于生理过程的时间依赖性模型，包含Ca2+运输、横桥循环和ATP再生的能量消耗预测。模型在多种收缩条件下验证，能准确捕捉收缩频率对峰值能量率的影响以及能量恢复的时间进程，且参数少、计算成本低，便于跨肌肉和物种推广应用。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有模型忽略肌肉收缩时间依赖性和ATP再生恢复成本，无法准确预测循环收缩下的能量消耗。
method: 构建包含Ca2+运输、横桥循环和ATP再生的时间依赖性生物力学模型，参数来自离体肌肉实验数据。
result: 验证表明模型能捕捉收缩频率对峰值能量率的影响及实验观察到的能量恢复时间进程。
conclusion: 模型在保持最少参数和低计算成本下，实现了跨肌肉和物种的通用性，可嵌入大规模肌肉骨骼模型。
---

## 摘要
预测骨骼肌在不同收缩条件下的能量消耗对于理解运动至关重要。现有数学模型虽然捕捉了能量消耗过程的机械依赖性，但忽略了与ATP再生相关的时间依赖性行为和恢复成本。这种时间依赖性对于预测肌肉在重复性或周期性任务（如运动）中的能量响应非常重要，因为肌肉会经历多次收缩周期。本研究提出了一种基于生理过程的新型模型来预测能量消耗率：Ca2+运输成本、横桥循环成本和ATP再生。以往的数学模型包含了Ca2+运输和横桥循环的依赖性，但忽略了时间依赖性响应以及收缩后ATP的后续恢复。模型参数来自离体肌肉制剂的现有数据，并在包括动态、次最大和单次收缩在内的多种收缩条件下的单独数据集上验证了预测的能量消耗率。该时间依赖性模型能够捕捉收缩频率对峰值能量消耗率的影响以及实验观察到的能量恢复的时间进程。该模型在保持最少自由参数和低计算成本的同时，捕捉了关键的生理过程。这使得模型能够跨肌肉和物种通用，并能够集成到更大规模的肌肉骨骼模型中。

## Abstract
Predictions of skeletal muscle energy consumption under a diverse range of muscle contractile conditions are critical for improving our understanding of locomotion. Existing mathematical models, while capturing the mechanical dependence of energy consuming processes, neglect the time-dependent behaviour and recovery costs associated with regenerating ATP. This time-dependence is important for predicting the energetic response of muscles during repetitive or cyclical tasks like locomotion, where muscle undergoes many contraction cycles. This study presents a novel model to predict energetic rates based on physiological processes: Ca2+ transport costs, cross-bridge cycling costs, and ATP regeneration. Previous mathematical models include the dependence on Ca2+ transport and cross-bridge cycling, but neglect the time-dependent response and the subsequent recovery of ATP following the contraction. Model parameters were obtained from existing data on isolated muscle preparations, and predicted energetic rates were validated on separate datasets across a range of contractile conditions including dynamic, sub-maximal, and twitch contractions. The time-dependent model was able to capture the influence of contraction frequency on peak energetic rates and the time-course of energetic recovery observed experimentally. The model captures key physiological processes while maintaining a minimal number of free parameters and low computational cost. This enables generalis-ability across muscles and species, and implementation into larger scale musculoskeletal models.