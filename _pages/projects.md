---
permalink: /projects/
title: "Research Projects"
author_profile: true
---

<span class="anchor" id="projects"></span>

# Research Projects

These projects develop compact, reusable memory representations for long and irregular sequences.

<article class="project-card">
  <h2>KronHiPPO-STGP</h2>
  <p class="publication-meta">Online Bayesian spatiotemporal modeling with evolving memory · Manuscript under review</p>
  <p>Spatiotemporal streams require both global trends and correlated uncertainty while observations arrive sequentially. KronHiPPO-STGP jointly updates a parametric linear trend and a Gaussian-process residual with a separable spatiotemporal kernel. Online HiPPO-SVGP maintains a fixed-size temporal history representation; spherical-Bessel evaluations replace numerical ODE integration, while Kronecker structure reduces posterior computation from O(M<sup>6</sup>) to O(M<sup>3</sup>). Experiments across climate, public-health, and traffic data show memory use independent of stream length together with accurate predictions and uncertainty quantification.</p>
  <p class="publication-links"><a class="btn btn--small" href="{{ '/files/KronHiPPO_STGP.pdf' | relative_url }}">Preview (first page)</a> <span class="btn btn--small btn--disabled" aria-disabled="true" title="Code repository is currently private">Code (private)</span></p>
</article>

<article class="project-card">
  <h2>HiPPO Functional Memory</h2>
  <p class="publication-meta">Coordinate-queryable attention for irregular time series · Manuscript under review</p>
  <p>Irregular time series require temporal queries at arbitrary coordinates, but observation-dependent representations often need repeated resolution. HiPPO Functional Memory compiles an irregular history into a reusable, coordinate-addressable state: observations are written into a fixed-rank functional space and queries are evaluated directly through matched functional geometry. Kernel-smoothed HiPPO coordinates, Gram-based readout, and observed-support self-attention support content-dependent compression while preserving coordinate semantics. The method characterizes a finite-dimensional query space and separates functional-geometry approximation error from learned-memory mismatch. Across reconstruction, irregular representation learning, real-world extrapolation, and event-sequence prediction, including 20 UEA datasets, the compact O(Md) state can be reused across query sets without re-encoding the observation history.</p>
  <p class="publication-links"><a class="btn btn--small" href="{{ '/files/HiPPO_Functional_Memory.pdf' | relative_url }}">Preview (first page)</a> <span class="btn btn--small btn--disabled" aria-disabled="true" title="Code repository is currently private">Code (private)</span></p>
</article>

<article class="project-card">
  <h2>Analytic Interdomain Memory for Efficient Online HiPPO-SVGP</h2>
  <p class="publication-meta">ICML 2026 Workshop on Structured Probabilistic Inference &amp; Generative Modeling</p>
  <p>Online Gaussian processes combine flexible function modeling with calibrated uncertainty, but exact inference is cubic and sparse online updates can forget early observations. This work replaces ODE-based HiPPO-LegS interdomain kernel construction with closed-form spherical-Bessel expressions for sine/cosine-Legendre overlaps. Kernel quantities are evaluated directly at the current time, removing ODE discretization error and reducing dependence on integration steps. On Solar Irradiance and COVID-19 mortality streams, the analytic variant retains comparable predictive performance and shows favorable aggregate metrics, with the strongest runtime gains at fine time discretizations.</p>
  <p class="publication-links"><a class="btn btn--small" href="{{ '/files/Analytic_Interdomain_Memory_HiPPO_SVGP.pdf' | relative_url }}">PDF</a> <a class="btn btn--small" href="https://github.com/zhaodong929/Analytic-HippoSVGP">Code</a></p>
</article>
