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
  <p><strong>Problem.</strong> Streaming spatiotemporal systems need to update uncertainty without replaying the full history.</p>
  <p><strong>Idea.</strong> Evolving HiPPO inducing representations transfer accumulated natural parameters between successive memories, with Kronecker-structured posterior computation.</p>
  <p><strong>Contribution.</strong> A bounded-memory online Bayesian model for streaming spatiotemporal prediction.</p>
</article>

<article class="project-card">
  <h2>HiPPO Functional Memory</h2>
  <p class="publication-meta">Coordinate-queryable attention for irregular time series · Manuscript under review</p>
  <p><strong>Problem.</strong> Irregular sequences require queries at new coordinates without repeatedly re-encoding the history.</p>
  <p><strong>Idea.</strong> A fixed-rank functional memory matches the write and read geometry and supports coordinate-level queries after encoding.</p>
  <p><strong>Contribution.</strong> O(Md) post-encoding storage for reusable sequence memory.</p>
</article>

<article class="project-card">
  <h2>Analytic Interdomain Memory for Efficient Online HiPPO-SVGP</h2>
  <p class="publication-meta">ICML 2026 Workshop on Structured Probabilistic Inference &amp; Generative Modeling</p>
  <p><strong>Problem.</strong> ODE-based interdomain kernel construction can depend on discretization choices.</p>
  <p><strong>Idea.</strong> An analytic spherical-Bessel formulation replaces the ODE construction while retaining comparable predictive accuracy.</p>
  <p><strong>Contribution.</strong> A more direct analytic route to efficient online HiPPO-SVGP inference.</p>
</article>
