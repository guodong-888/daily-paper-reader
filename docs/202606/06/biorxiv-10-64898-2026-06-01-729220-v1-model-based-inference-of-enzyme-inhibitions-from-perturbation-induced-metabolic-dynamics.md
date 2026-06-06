---
title: Model-based inference of enzyme inhibitions from perturbation-induced metabolic dynamics
title_zh: 基于模型的酶抑制推断：从扰动诱导的代谢动力学出发
authors: "Liebermeister, W., Pauletti, M., dorcakova, T., Rahm, C., Zampieri, M."
date: 2026-06-03
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.01.729220v1.full.pdf"
tags: ["query:flap-ex-met"]
score: 7.0
evidence: 提供了一个从动态代谢组学数据推断代谢酶抑制的计算框架，可应用于研究运动诱导的皮瓣代谢变化
tldr: 代谢在微生物快速适应环境挑战中起关键作用，但代谢组学数据缺乏计算方法解释扰动传播机制。本文提出IMF框架，通过线性化非线性动力学并利用集合采样绕过未知参数，在E. coli中心代谢模型上成功推断扰动靶点。该方法为时域代谢组学数据的设计、分析和解释提供了有效途径。
source: biorxiv
selection_source: fresh_fetch
motivation: 代谢组学数据难以计算解释扰动如何通过代谢网络传播产生变化，缺乏机械性理解方法。
method: 提出IMF框架，假设小扰动并线性化动力学方程，结合集合采样高效推断扰动靶点。
result: 在E. coli中心代谢模型上，利用模拟和实验数据成功推断代谢扰动的酶靶点。
conclusion: IMF为时域代谢组学数据的设计、分析和解释提供了有效方法。
---

## 摘要
在微生物中，代谢在应对突然挑战（如营养限制或有毒化合物）的首次快速适应中起关键作用。虽然代谢组学能够分析刺激诱导的代谢变化，但能够解释这些数据以机械地说明扰动如何通过代谢传播并产生所观察到的变化的计算方法仍显滞后。在此，我们开发了一个名为“从代谢指纹推断”（IMF）的计算框架，用于建模对代谢扰动的即时动态响应，并系统地推断其入口点（即酶靶点）。IMF假设小扰动并围绕参考稳态对非线性动力学进行线性化。这使得IMF能够扩展到大型代谢网络，并通过允许快速高效的集成采样绕过缺失的动力学参数。我们将IMF应用于大肠杆菌中心代谢的模型。使用计算机模拟和实验数据，我们展示了即使在未知动力学参数和不完整代谢数据的情况下，也能够推断代谢扰动的靶点。因此，我们表明IMF是设计、分析和解释时间分辨代谢组学的有效方法。

## Abstract
In microbes, metabolism plays a key role in the first rapid adaptation to sudden challenges such as nutrient limitations or toxic compounds. While metabolomics enables the profiling of stimuli-induced metabolic changes, computational approaches that can interpret these data to mechanistically explain how perturbations propagate through metabolism to produce the observed changes are lagging behind. Here, we developed a computational framework, called Inference from Metabolic Fingerprints (IMF), to model the immediate dynamic response to a metabolic perturbation and systematically infer its entry point (i.e. enzymatic target). IMF assumes small perturbations and linearizes the nonlinear dynamics around a reference steady state. This allows IMF to scale with large metabolic networks and bypass missing kinetic parameters by allowing for fast and efficient ensemble sampling. We apply IMF to a model of central metabolism in Escherichia coli. Using in-silico and experimental data, we demonstrate the ability to infer the target of metabolic perturbations in spite of unknown kinetic parameters and incomplete metabolic data. Hence, we show that IMF is an effective approach for designing, analyzing and interpreting time-resolved metabolomics.