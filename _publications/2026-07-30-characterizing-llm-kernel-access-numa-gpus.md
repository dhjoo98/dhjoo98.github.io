---
title: "Characterizing LLM Kernel Access and Memory Interaction in Multi-Partition NUMA GPUs"
collection: publications
category: preprints
permalink: /publication/2026-07-30-characterizing-llm-kernel-access-numa-gpus
excerpt: 'A memory trace analysis of how LLM workloads interact with multi-partition NUMA GPU architectures, categorizing kernel operands into global, partial, and private sharing patterns.'
date: 2026-07-30
venue: 'arXiv preprint arXiv:2607.28824'
paperurl: 'https://arxiv.org/abs/2607.28824'
citation: 'Donghyeon Joo, Sooraj Puthoor, Nuwan Jayasena, Bahar Asgari. (2026). &quot;Characterizing LLM Kernel Access and Memory Interaction in Multi-Partition NUMA GPUs.&quot; <i>arXiv preprint arXiv:2607.28824</i>.'
---

This work examines how large language model workloads interact with multi-partition GPU architectures, where non-uniform memory access characteristics and inter-partition communication can amplify contention and degrade performance. We develop a memory trace analysis methodology to study data access patterns at the workgroup level, categorizing kernel operands into three sharing patterns — global, partial, and private — and recommend placement-aware kernel programming and smarter architectural support for work and data locality.

[View on arXiv](https://arxiv.org/abs/2607.28824)
