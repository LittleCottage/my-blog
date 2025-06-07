---
title: "Understanding the Transformer"
categories: [AI]
tags: [transformer, attention]
---

The Transformer is a model based on attention mechanisms:

$$
\text{Attention}(Q, K, V) = \text{softmax}\left( \frac{QK^T}{\sqrt{d_k}} \right)V
$$
