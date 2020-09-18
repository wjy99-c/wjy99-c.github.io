---
title: "QuanFuzz: Fuzz Testing of Quantum Program"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2009-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Jiyuan Wang, Ming Gao, Yu Jiang, Jianguang Lou, Yue Gao, Dongmei Zhang, Jiaguang Sun. (2018).'
---

In this paper, we present QuanFuzz, a search-based test input generator for quantum program. We define the quantum sensitive information to evaluate test input for quantum program and use matrix generator to generate test cases with higher coverage. First, we extract quantum sensitive information -- measurement operations on those quantum registers and the sensitive branches associated with those measurement results, from the quantum source code. Then, we use the sensitive information guided algorithm to mutate the initial input matrix and select those matrices which improve the probability weight for a value of the quantum register to trigger the sensitive branch. The process keeps iterating until the sensitive branch triggered. We tested QuanFuzz on benchmarks and acquired 20% - 60% more coverage compared to traditional testing input generation.

[Download paper here](https://arxiv.org/pdf/1810.10310.pdf)

Recommended citation: Jiyuan Wang, Ming Gao, Yu Jiang, Jianguang Lou, Yue Gao, Dongmei Zhang, Jiaguang Sun. (2018).