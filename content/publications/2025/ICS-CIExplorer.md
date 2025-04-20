---
title: "CIExplorer: Microarchitecture-Aware Exploration for Tightly Integrated Custom Instruction"
FirstAuthor:
- Xiaoyu Hao
OtherAuthors:
- Sen Zhang
- Liang Qiao
- Qingcai Jiang
- Jun Shi
- Junshi Chen
- Hong An
- Xulong Tang
- Hao Shu
- Honghui Yuan

ConfJournal: "The 38th ACM International Conference on Supercomputing 2025"
ConfJournalAbbr: ICS
IsAConference: "yes" # 会议填yes，期刊写 no
IsOutofCS: "no" # 其他领域会议，填yes (比如医疗影响领域会议)
OutofCSLabel: "" # 医疗影像领域会议
CCFLevel: "B" 
JournalLabel: "" # SCI Q1, IF=5.7 
Year: 2025
Award: ""
Abstract: ""
KeyWords:
- Custom instruction
- Microarchitecture
- HW/SW codesign

Link: # 官网链接 
PDF: # pdf文件位置
SLIDE:  # PPT文件位置
video: # 会议视频
---

Extending existing architectures with customized instruction extensions is emerging to achieve high performance and energy efficiency for specific applications. Automated discovery of custom instructions (CIs) is well-studied nowadays, which requires exploring combinations of different types and quantities of operations, resulting in a vast search space.
However, previous works typically use microarchitecture-agnostic cost models, leading to suboptimal CIs that may degrade performance. They leverage graph isomorphism to reduce area overhead, but few of them consider its potential to benefit performance-oriented exploration.
To this end, we present CIExplorer, a framework for CI exploration. We propose a Seed Growth Method based on a genetic algorithm to discover CIs with the consideration of graph similarity. We also propose a compiler-assisted modeling strategy that applies a microarchitecture-aware cost model to estimate the potential benefits of CIs for different microarchitectures.
 We evaluate our framework using various benchmarks in SPEC2006 and Mediabench on in-order, 2-wide OOO, and 4-wide OOO processors. 
Experimental results demonstrate that CIExplorer achieves average performance improvements of 1.09$\times$ and 1.13$\times$ and energy improvements of 1.07$\times$ and 1.10$\times$ compared with Novia and MaxClique.

