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

I am an **MRes researcher in Artificial Intelligence and Machine Learning** at Imperial College London, and completed the MRes with **Distinction** under the supervision of **Prof. Yingzhen Li**.

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
  <p>Spatiotemporal streams require both global trends and correlated uncertainty while observations arrive sequentially. KronHiPPO-STGP jointly updates a parametric linear trend and a Gaussian-process residual with a separable spatiotemporal kernel. Online HiPPO-SVGP maintains a fixed-size temporal history representation; spherical-Bessel evaluations replace numerical ODE integration, while Kronecker structure reduces posterior computation from O(M<sup>6</sup>) to O(M<sup>3</sup>). Experiments across climate, public-health, and traffic data show memory use independent of stream length together with accurate predictions and uncertainty quantification.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://arxiv.org/">arXiv</a> <a class="btn btn--small" href="{{ '/files/KronHiPPO_STGP.pdf' | relative_url }}">Preview (first page)</a> <span class="btn btn--small btn--disabled" aria-disabled="true" title="Code repository is currently private">Code (private)</span></p>
</article>

<article class="publication-card">
  <h2>HiPPO Functional Memory: Coordinate-Queryable Attention for Irregular Time Series</h2>
  <p class="publication-meta">Manuscript under review</p>
  <p>Irregular time series require temporal queries at arbitrary coordinates, but observation-dependent representations often need repeated resolution. HiPPO Functional Memory compiles an irregular history into a reusable, coordinate-addressable state: observations are written into a fixed-rank functional space and queries are evaluated directly through matched functional geometry. Kernel-smoothed HiPPO coordinates, Gram-based readout, and observed-support self-attention support content-dependent compression while preserving coordinate semantics. The method characterizes a finite-dimensional query space and separates functional-geometry approximation error from learned-memory mismatch. Across reconstruction, irregular representation learning, real-world extrapolation, and event-sequence prediction, including 20 UEA datasets, the compact O(Md) state can be reused across query sets without re-encoding the observation history.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://arxiv.org/abs/2610.24501">arXiv</a> <a class="btn btn--small" href="{{ '/files/HiPPO_Functional_Memory.pdf' | relative_url }}">Preview (first page)</a> <span class="btn btn--small btn--disabled" aria-disabled="true" title="Code repository is currently private">Code (private)</span></p>
</article>

<article class="publication-card">
  <h2>Analytic Interdomain Memory for Efficient Online HiPPO-SVGP</h2>
  <p class="publication-meta">Zhaodong Guo, Naoki Kiyohara, Wenlong Chen, Harrison Bo Hua Zhu, Yingzhen Li · ICML 2026 Workshop on Structured Probabilistic Inference &amp; Generative Modeling</p>
  <p>Online Gaussian processes combine flexible function modeling with calibrated uncertainty, but exact inference is cubic and sparse online updates can forget early observations. This work replaces ODE-based HiPPO-LegS interdomain kernel construction with closed-form spherical-Bessel expressions for sine/cosine-Legendre overlaps. Kernel quantities are evaluated directly at the current time, removing ODE discretization error and reducing dependence on integration steps. On Solar Irradiance and COVID-19 mortality streams, the analytic variant retains comparable predictive performance and shows favorable aggregate metrics, with the strongest runtime gains at fine time discretizations.</p>
  <p class="publication-links"><a class="btn btn--small" href="https://icml.cc/virtual/2026/74293">ICML Page</a> <a class="btn btn--small" href="{{ '/files/Analytic_Interdomain_Memory_HiPPO_SVGP.pdf' | relative_url }}">PDF</a> <a class="btn btn--small" href="https://github.com/zhaodong929/Analytic-HippoSVGP">Code</a></p>
</article>

<span class="anchor" id="news"></span>

# News

- *2026*: HiPPO Functional Memory manuscript submitted.
- *2026*: Analytic Interdomain Memory presented at the ICML 2026 Workshop.
- *2026*: Completed MRes research on KronHiPPO-STGP at Imperial College London.

<span class="anchor" id="cv"></span>

# CV

<p><a class="btn btn--primary" href="{{ '/files/Zhaodong_Guo_CV.pdf' | relative_url }}">Download CV (PDF)</a></p>
