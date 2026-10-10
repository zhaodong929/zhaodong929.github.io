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

I am an **MRes student in Artificial Intelligence and Machine Learning** at Imperial College London, supervised by **Prof. Yingzhen Li**.

My research focuses on building **efficient learning systems with structured and persistent memory** for long and irregular sequences. I study how compact representations, state-space models, and probabilistic inference can enable models to continuously update and retrieve information over extended horizons.

My recent work explores **HiPPO-based functional memory, online Bayesian spatiotemporal modeling, and efficient attention mechanisms**, with the goal of developing scalable memory architectures for time-series foundation models, long-context models, and AI agents.

<span class="anchor" id="research"></span>

# Research

My research investigates how AI systems can maintain and use information efficiently over long horizons. My **research interests and future directions** include:

- **Efficient foundation models** and structured memory architectures;
- **state-space representations** and long-context learning;
- **online Bayesian inference** for adaptive spatiotemporal modeling; and
- structured memory for **time-series foundation models, long-context language models, memory-augmented agents, and efficient AI systems**.

<span class="anchor" id="publications"></span>

# Publications

<article class="publication-card">
  <h2>KronHiPPO-STGP: Online Bayesian Spatiotemporal Modeling with Evolving Memory</h2>
  <p class="publication-meta">Manuscript under review</p>
  <p>A bounded-memory online Bayesian model that combines evolving HiPPO representations, natural-parameter transfer, and structured inference for streaming spatiotemporal prediction.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://arxiv.org/">arXiv</a> <a class="btn btn--small" href="{{ '/files/KronHiPPO_STGP.pdf' | relative_url }}">PDF</a> <a class="btn btn--small" href="https://github.com/zhaodong929/Kronecker_Separable_Spatio_Temporal_HiPPO_SVGP">Code</a></p>
</article>

<article class="publication-card">
  <h2>HiPPO Functional Memory: Coordinate-Queryable Attention for Irregular Time Series</h2>
  <p class="publication-meta">Manuscript under review</p>
  <p>A fixed-rank functional memory that supports coordinate-level queries without re-encoding, with matched write/read geometry and O(Md) post-encoding storage.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://arxiv.org/">arXiv</a> <a class="btn btn--small" href="{{ '/files/HiPPO_Functional_Memory.pdf' | relative_url }}">PDF</a> <a class="btn btn--small" href="https://github.com/zhaodong929/Kronecker_Separable_Spatio_Temporal_HiPPO_SVGP">Code</a></p>
</article>

<article class="publication-card">
  <h2>Analytic Interdomain Memory for Efficient Online HiPPO-SVGP</h2>
  <p class="publication-meta">Zhaodong Guo, Naoki Kiyohara, Wenlong Chen, Harrison Bo Hua Zhu, Yingzhen Li · ICML 2026 Workshop on Structured Probabilistic Inference &amp; Generative Modeling</p>
  <p>Replaces ODE-based HiPPO interdomain kernel construction with an analytic spherical-Bessel formulation, reducing dependence on ODE discretization while retaining comparable predictive accuracy.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://icml.cc/virtual/2026/74293">ICML Page</a> <a class="btn btn--small" href="{{ '/files/Analytic_Interdomain_Memory_HiPPO_SVGP.pdf' | relative_url }}">PDF</a> <a class="btn btn--small" href="https://github.com/zhaodong929/Multi-SVGP">Code</a></p>
</article>

<span class="anchor" id="news"></span>

# News

- *2026*: HiPPO Functional Memory manuscript submitted.
- *2026*: Analytic Interdomain Memory presented at the ICML 2026 Workshop.
- *2026*: Completed MRes research on KronHiPPO-STGP at Imperial College London.

<span class="anchor" id="cv"></span>

# CV

<p><a class="btn btn--primary" href="{{ '/files/Zhaodong_Guo_CV.pdf' | relative_url }}">Download CV (PDF)</a></p>

The arXiv buttons currently point to the arXiv homepage until paper identifiers are available.
