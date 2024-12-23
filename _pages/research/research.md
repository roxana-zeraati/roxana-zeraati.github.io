---
layout: home
permalink: /research/
title: "Research"
excerpt: "An overview of my research."
search_omit: false
headline: 
layout: single
author_profile: false
---

## Current and future research

{: style="text-align: justify" }
I am generally interested in developing methods and models that would allow us to gain a mechanistic understanding of adaptive learning and behavior in naturalistic settings. While I find task-optimized RNNs a useful tool to directly study the relation between learning, dynamics, computation, and behavior, I believe their emergent solutions largely depend on the training process (e.g., curriculum). More importantly, the conventional supervised training algorithms of RNNs do not resemble the learning process in biological systems. As a result, the uncovered mechanisms by these models may also differ from those of biological systems (e.g., classic RNNs are incapable of mistakes and biases similar to animals). In the course of searching for alternative learning algorithms, I realized reinforcement learning (RL) is probably the closest to biological learning in naturalist settings. Therefore, RL can be a potential framework to address the problems with the conventional approaches for training RNNs.


{: style="text-align: justify" }
That is why, in the next step, I will focus on the intersection between RL models and RNNs. More specifically, training RNNs (ideally biophysically plausible ones) to perform complex behaviors, and reverse-engineering them to understand the mechanisms underlying adaptive learning in dynamic ecological environments. 

## Past research

{: style="text-align: justify" }
During my PhD, I studied how spatiotemporal scales of neural dynamics relate to behavior during different cognitive tasks. First, we developed data analysis methods ([Zeraati et al., Nat. Comput. Sci, 2022](https://www.nature.com/articles/s43588-022-00214-3)) and computational models ([Zeraati et al., Nat. Commun., 2023](https://www.nature.com/articles/s41467-023-37613-7); [Shi, Zeraati et al., PRR, 2023](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.013005)) to show that timescales of neural dynamics can flexibly adapt to behavioral states (e.g., selective attention), correlate with behavioral outputs such as reaction time, and are shaped by the spatial network structure and top-down inputs.  I also worked on a project in collaboration with the International Brain Laboratory, where we studied the role of diverse neural timescales across the whole mouse brain (especially in subcortical structures such as the midbrain and hindbrain) during decision-making.


{: style="text-align: justify" }
Inspired by these findings, I became interested in the functional role of neural timescales, i.e. their role in neural computations. For this purpose, we used task-optimized recurrent neural networks (RNNs) to study the link between neural timescales and working memory ([Khajehabdollahi<sup>*</sup>, Zeraati<sup>*</sup> et al., ICLR, 2024](https://openreview.net/forum?id=xwKt6bUkXj)). We found that slow timescales required for forming long memories arise from distinct mechanisms shaped by the learning curriculum: developing slow timescales using recurrent dynamics instead of single-neuron biophysical properties allows learning more complex objectives and improves computational robustness. Our results also introduced optimal training algorithms for other machine-learning architectures, e.g., GRU and LSTM. 



## Recorded talks

Cosyne 2024 Main Meeting: Long timescales needed for memory tasks arise from distinct mechanisms shaped by learning curricula.
<iframe width="560" height="315" src="https://www.youtube.com/embed/OCr4KV653u8?si=8-Vefe5P8qPilMAg&amp;start=5103" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
&nbsp;  



Cosyne 2024 Workshops: A census of neural timescales across the mouse brain.
<iframe width="560" height="315" src="https://www.youtube.com/embed/lUS7OCB12D8?si=QoSxIJ3H6NSNmm-r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>




