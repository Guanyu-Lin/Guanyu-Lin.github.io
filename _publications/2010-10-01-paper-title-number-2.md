---
title: "Dual-interest Factorization-heads Attention for Sequential Recommendation."
collection: publications
permalink: /publication/2023-10-01-paper-title-number-2
excerpt: 'Accurate user interest modeling is vital for recommendation scenarios. One of the efective solutions is the sequential recommendation that relies on click behaviors, but thisis not elegant in the video feed recommendation where users are passive in receiving the streaming contents and return skip or no-skip behaviors. Here skip and no-skip behaviors can be treated as negative and positive feedback,
respectively. With the mixture of positive and negative feedback,
it is challenging to capture the transition pattern of behavioral
sequence. To do so, FeedRec has exploited a shared vanilla Transformer, which may be inelegant because head interaction of multiheads attention does not consider diferent types of feedback. In
this paper, we propose Dual-interest Factorization-heads Attention
for Sequential Recommendation (short for DFAR) consisting of
feedback-aware encoding layer, dual-interest disentangling layer
and prediction layer. In the feedback-aware encoding layer, we frst
suppose each head of multi-heads attention can capture specifc
feedback relations. Then we further propose factorization-heads
attention which can mask specifc head interaction and inject feedback information so as to factorize the relation between diferent
types of feedback. Additionally, we propose a dual-interest disentangling layer to decouple positive and negative interests before
performing disentanglement on their representations. Finally, we
evolve the positive and negative interests by corresponding towers
whose outputs are contrastive by BPR loss. Experiments on two
real-world datasets show the superiority of our proposed method
against state-of-the-art baselines. Further ablation study and visualization also sustain its efectiveness. We release the source code
here: https://github.com/tsinghua-fb-lab/WWW2023-DFAR.'
date: 2023-05-01
venue: 'In Proceedings of the ACM Web Conference 2023'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3543507.3583278'
citation: 'Guanyu Lin. (2023). &quot;Dual-interest Factorization-heads Attention for Sequential Recommendation.&quot; <i> In Proceedings of the ACM Web Conference 2023 </i>.'
---
**Guanyu Lin**, Chen Gao, Yu Zheng, Jianxin Chang, Yanan Niu, Yang Song, Zhiheng Li, Depeng Jin, Yong Li.

[Download paper here](https://dl.acm.org/doi/pdf/10.1145/3543507.3583278)

