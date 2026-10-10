---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about"></span>

I am an MRes researcher in Artificial Intelligence and Machine Learning at Imperial College London, supervised by Prof. Yingzhen Li. My research focuses on compact and reusable memory representations for long and irregular sequences, including HiPPO-based functional memory, structured online Bayesian inference, and efficient attention. I am particularly interested in extending these ideas toward time-series foundation models, long-context models, and agent memory.

## Research interests

Structured memory, efficient sequence modeling, irregular time series, long-context modeling, time-series foundation models, and agent memory.

<span class="anchor" id="research"></span>

# Research

My current research develops fixed-size representations that can be updated online and queried at new coordinates without revisiting the full history. The projects below cover functional memory for irregular sequences, Bayesian spatiotemporal inference, and analytic interdomain kernels for online Gaussian processes.

<span class="anchor" id="publications"></span>

# Publications

<article class="publication-card">
  <h2>HiPPO Functional Memory: Coordinate-Queryable Attention for Irregular Time Series</h2>
  <p class="publication-meta">Authors anonymized for review · Preprint / manuscript under review</p>
  <p>A fixed-rank functional memory that supports coordinate-level queries without re-encoding, with matched write/read geometry and O(Md) post-encoding storage.</p>
  <p class="publication-links"><a class="btn btn--small" href="#">arXiv</a> <a class="btn btn--small" href="#">PDF</a> <a class="btn btn--small" href="#">Code</a></p>
</article>

<article class="publication-card">
  <h2>KronHiPPO-STGP: Online Bayesian Spatiotemporal Modeling with Evolving Memory</h2>
  <p class="publication-meta">Authors anonymized for review · Preprint / manuscript under review</p>
  <p>Replay-free online Bayesian inference with evolving HiPPO inducing representations, projection of accumulated natural parameters across successive representations, and Kronecker-structured posterior computation.</p>
  <p class="publication-links"><a class="btn btn--small" href="#">arXiv</a> <a class="btn btn--small" href="#">PDF</a></p>
</article>

<article class="publication-card">
  <h2>Analytic Interdomain Memory for Efficient Online HiPPO-SVGP</h2>
  <p class="publication-meta">Zhaodong Guo, Naoki Kiyohara, Wenlong Chen, Harrison Bo Hua Zhu, Yingzhen Li · ICML 2026 Workshop on Structured Probabilistic Inference &amp; Generative Modeling</p>
  <p>Replaces ODE-based HiPPO interdomain kernel construction with an analytic spherical-Bessel formulation, reducing dependence on ODE discretization while retaining comparable predictive accuracy.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://icml.cc/virtual/2026/74293">ICML Page</a> <a class="btn btn--small" href="#">PDF</a> <a class="btn btn--small" href="#">Code</a></p>
</article>

# News

- *2026*: HiPPO Functional Memory manuscript submitted.
- *2026*: Analytic Interdomain Memory presented at the ICML 2026 Workshop.
- *2026*: Completed MRes research on KronHiPPO-STGP at Imperial College London.

<span class="anchor" id="cv"></span>

# CV

[Download my CV](files/Zhaodong_Guo_CV.pdf)

Publication links marked with `#` are placeholders for the final public versions and code repositories.
