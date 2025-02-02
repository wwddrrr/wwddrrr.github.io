---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


**Machine Learning and Hyperdimensional Computing**  

<span style="color:lightgray; font-size: smaller;">Python, R    Collaborated with Yinan Bu</span>  

- Hyperdimensional computing (HDC) is an efficient, interpretable, and robust computing method based on the calculation of hypervectors.  
- We integrated this method with ensemble learning and demonstrated its superiority across multiple diseases.  
- Applied this approach to data from the UK Biobank and designed several models for data processing and embedding.  
- Trained the HDC model and predicted the prevalence rates of various illnesses.

---------------------------------------------

**Reinforcement Learning AI for GuanDan (a Chinese card game)**

<span style="color:lightgray; font-size: smaller;">Python    Collaborated with Xiaopu Wang</span>

- This project aims to train a reinforcement learning AI capable of playing GuanDan. One of the key challenges in training such an AI arises from the presence of wildcard cards, which significantly expand the action space. This complexity makes it difficult to effectively train a Q-network.
- Trained a Q-network to evaluate the value of different card-playing choices.
- Developed a transformer-based model for hand card planning and decomposition in Guandan to narrow the action selection space and make choices within a more optimal range.
- Retrain the Q-network with improved choices derived from the card decomposition model.


-------------------------------------------------

**A Highly Scalable Parallel Algorithm for Trend Filtering on Graphs**

<span style="color:lightgray; font-size: smaller;">Python    Collaborated with Yinan Bu, Yihong Zuo</span>

- Graph trend filtering is a powerful nonparametric method that extracts piecewise smooth graph signals by minimizing the ℓ₁ norm of discrete graph differences.
- Traditional ADMM algorithms often struggle with the trade-off between convergence speed and the tractability of subproblems, leading to computational inefficiencies.
- We propose Doge-ADMM, a novel Differential Operator Grouping-based ADMM algorithm that enables scalable parallel computation while maintaining closed-form solutions for subproblems.
- Experiments on 2D grid graphs show that Doge-ADMM achieves up to 30× acceleration over state-of-the-art methods in second-order trend filtering, making it highly effective for large-scale graph-based problems.
- [Project Page](https://github.com/byn1002/Doge-ADMM)
