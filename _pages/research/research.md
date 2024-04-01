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

## Past and current research

{: style="text-align: justify" }
During my PhD, I studied how spatiotemporal scales of neural dynamics relate to behavior during different cognitive tasks. First, we developed data analysis methods ([Zeraati et al., Nat. Comput. Sci, 2022](https://www.nature.com/articles/s43588-022-00214-3)) and computational models ([Zeraati et al., Nat. Commun., 2023](https://www.nature.com/articles/s41467-023-37613-7); [Shi, Zeraati et al., PRR, 2023](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.013005)) to show that timescales of neural dynamics can flexibly adapt to behavioral states (e.g., selective attention), correlate with behavioral outputs such as reaction time, and are shaped by the spatial network structure and top-down inputs. Currently, I am working on a project in collaboration with the [International Brain Laboratory](https://www.internationalbrainlab.com/), where we study the role of diverse neural timescales across the whole mouse brain (especially in sub-cortical structures such as the midbrain, hindbrain and cerebellum) during decision-making. 


Inspired by our previous findings, then, I became interested in the functional role of neural timescales, i.e. their role in neural computations. For this purpose, we used task-optimized recurrent neural networks (RNNs) to study the link between neural timescales and working memory ([Khajehabdollahi*, Zeraati* et al., ICLR, 2024](https://openreview.net/forum?id=xwKt6bUkXj). We found that slow timescales required for forming long memories arise from distinct mechanisms shaped by the learning curriculum: developing slow timescales using recurrent dynamics instead of single-neuron biophysical properties allows learning more complex objectives and improves computational robustness. Our results also introduced optimal training algorithms for other machine-learning architectures, e.g., GRU and LSTM. 

## Potential future directions

I am generally interested in developing methods and models that would allow us to gain a mechanistic understanding of adaptive learning in naturalistic settings. While I find task-optimized RNNs a useful tool to directly study the relation between learning, dynamics, computation, and behavior, I believe their emergent solutions largely depend on the training process (e.g., curriculum). More importantly, the conventional supervised training algorithms of RNNs do not resemble the learning process in biological systems. As a result, the uncovered mechanisms by these models may also differ from those of biological systems (e.g., classic RNNs are incapable of mistakes and biases similar to animals). In the course of searching for alternative learning algorithms that biological systems may use, I realized reinforcement learning (RL) is probably the closest to biological learning in naturalist settings. Thus, RL may be able to address the mentioned problems with the conventional approaches for training RNNs.

That is why, in the next step, I would like to focus on the intersection between RL models and RNNs. More specifically, training RNNs (ideally biophysically plausible ones) to perform complex behaviors, and reverse-engineering them to understand the mechanisms underlying adaptive learning in dynamic ecological environments. 




