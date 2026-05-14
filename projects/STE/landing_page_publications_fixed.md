---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .intro-card {
    padding: 1.1rem 1.25rem;
    border: 1px solid #e8e8e8;
    border-radius: 10px;
    background: #fafafa;
    margin-bottom: 1.5rem;
  }

  .research-tags {
    margin-top: 0.8rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
  }

  .research-tag {
    display: inline-block;
    padding: 0.25rem 0.55rem;
    border-radius: 999px;
    background: #eef4fb;
    color: #24496f;
    font-size: 0.85rem;
    line-height: 1.3;
  }

  .news-list {
    display: flex;
    flex-direction: column;
    gap: 0.7rem;
    margin-top: 0.5rem;
  }

  .news-item {
    display: grid;
    grid-template-columns: 120px 1fr;
    column-gap: 1rem;
    align-items: start;
  }

  .news-date {
    font-weight: 700;
    color: #333;
  }

  .publication-list {
    display: block;
    width: 100%;
    margin-top: 0.75rem;
  }

  .publication-card {
    display: flex;
    flex-direction: row;
    gap: 1.1rem;
    align-items: flex-start;
    width: 100%;
    margin: 0 0 1.35rem 0;
    padding: 1rem;
    border: 1px solid #e8e8e8;
    border-radius: 10px;
    background: #fff;
    box-sizing: border-box;
    clear: both;
  }

  .publication-card::after {
    content: "";
    display: table;
    clear: both;
  }

  .publication-thumb {
    flex: 0 0 165px;
    max-width: 165px;
  }

  .publication-thumb img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 7px;
    border: 1px solid #eee;
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  }

  .publication-info {
    flex: 1 1 auto;
    min-width: 0;
  }

  .publication-title {
    font-size: 1.08rem;
    line-height: 1.35;
    font-weight: 700;
    margin-bottom: 0.25rem;
  }

  .publication-title a {
    text-decoration: none;
    color: inherit;
  }

  .publication-title a:hover {
    text-decoration: underline;
  }

  .publication-authors {
    font-size: 0.92rem;
    color: #666;
    margin-bottom: 0.2rem;
  }

  .publication-venue {
    font-size: 0.92rem;
    margin-bottom: 0.35rem;
  }

  .publication-summary {
    font-size: 0.92rem;
    color: #444;
    margin: 0.35rem 0 0.45rem 0;
    line-height: 1.45;
  }

  .publication-links {
    font-size: 0.92rem;
  }

  .publication-links a {
    margin-right: 0.55rem;
    white-space: nowrap;
  }

  @media (max-width: 700px) {
    .news-item {
      grid-template-columns: 1fr;
      row-gap: 0.15rem;
    }

    .publication-card {
      flex-direction: column;
    }

    .publication-thumb {
      flex: none;
      max-width: 100%;
      width: 100%;
    }

    .publication-thumb img {
      max-width: 260px;
    }
  }
</style>

<div class="intro-card">
I am a fifth-year Ph.D. candidate in the [Department of Statistics](https://stat.uw.edu/) at the University of Washington, advised by Prof. [Alex Luedtke](https://www.alexluedtke.com/). My research lies at the intersection of causal inference, optimal transport, nonparametric statistics, and machine learning.

At UW, I am fortunate to work with Profs. [Zaid Harchaoui](https://sites.google.com/uw.edu/zaid-harchaoui/main) and [Soumik Pal](https://sites.math.washington.edu//~soumik/). I also collaborate with the [Abrahms Lab](https://www.abrahmslab.com/) and the [eScience Institute](https://escience.washington.edu/) on developing AI tools for ecology.

<div class="research-tags">
  <span class="research-tag">Optimal transport</span>
  <span class="research-tag">Causal inference</span>
  <span class="research-tag">Gradient flows</span>
  <span class="research-tag">Nonparametric statistics</span>
  <span class="research-tag">Machine learning for ecology</span>
</div>
</div>

I completed my undergraduate degree in Mathematics at the [Indian Institute of Technology Kanpur](https://www.iitk.ac.in/), with a minor in English literature. At IIT Kanpur, I worked with [Dootika Vats](https://dvats.github.io) on output analysis and convergence diagnostics for Markov chain Monte Carlo and importance sampling.

Contact me at `medhaaga [at] uw [dot] edu`.

## News

<div class="news-list">

  <div class="news-item">
    <div class="news-date">May 2026</div>
    <div>Looking forward to attending the <a href="https://sites.google.com/view/ot-opt-2026/workshop?authuser=0">Optimal Transport + Optimization Workshop</a> in Les Diablerets, Switzerland.</div>
  </div>

  <div class="news-item">
    <div class="news-date">Winter 2026</div>
    <div>Looking forward to being a <b>Visiting Scholar</b> at Harvard Medical School.</div>
  </div>

  <div class="news-item">
    <div class="news-date">July 2025</div>
    <div>Our paper <a href="https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210x.70206">Leveraging machine learning and accelerometry to classify animal behaviours with uncertainty</a> was published in <i>Methods in Ecology and Evolution</i>.</div>
  </div>

  <div class="news-item">
    <div class="news-date">June 2025</div>
    <div>Looking forward to attending the workshop on <a href="https://www.birs.ca/events/2025/5-day-workshops/25w5430">Wasserstein Gradient Flows in Math and Machine Learning</a> at the Banff International Research Station.</div>
  </div>

  <div class="news-item">
    <div class="news-date">Feb 2025</div>
    <div>Gave a talk at the <a href="https://www.ifml.institute/events/mathematics-deep-learning-workshop">IFML Mathematics of Deep Learning Workshop</a> in Austin, TX. <a href="files/ifml.pdf">[Slides]</a></div>
  </div>

  <div class="news-item">
    <div class="news-date">Feb 2025</div>
    <div>Gave a talk at the <a href="https://escience.washington.edu/events/uw-data-science-seminar-kasim-rafiq-and-medha-agarwal/">UW Data Science Seminar</a>, titled <i>Revealing the Hidden Lives of Cryptic Carnivores with Machine Learning and AI</i>. Check out the <a href="https://www.youtube.com/watch?v=Y5jXkbXtCag">YouTube video</a>! <a href="files/eScience_seminar.pdf">[Slides]</a></div>
  </div>

</div>

## Selected Publications

<div class="publication-list">

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/projects/STE/static/thumbnail.png" alt="Thumbnail for Sinkhorn Treatment Effects project">
    </div>

    <div class="publication-info">
      <div class="publication-title">
        <a href="/projects/STE/">Sinkhorn Treatment Effects: A Causal Optimal Transport Measure</a>
      </div>
      <div class="publication-authors">
        <i><b>Medha Agarwal</b>, Alex Luedtke</i>
      </div>
      <div class="publication-venue">
        Accepted at <i>International Conference on Machine Learning</i> (2026)
      </div>
      <p class="publication-summary">
        A distributional treatment effect based on Sinkhorn divergence, with efficient first-order estimation and second-order null inference for testing equality of counterfactual outcome laws.
      </p>
      <div class="publication-links">
        <a href="https://arxiv.org/pdf/2605.08485v1">[Paper]</a>
        <a href="/projects/STE/">[Project Page]</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <img src="/projects/AWD-Biologging/static/thumbnail.png" alt="Thumbnail for animal behaviour classification project">
    </div>

    <div class="publication-info">
      <div class="publication-title">
        <a href="/projects/AWD-Biologging/">Leveraging machine learning and accelerometry to classify animal behaviours with uncertainty</a>
      </div>
      <div class="publication-authors">
        <i><b>Medha Agarwal</b>, Kasim Rafiq, Ronak Mehta, Briana Abrahms, Zaid Harchaoui</i>
      </div>
      <div class="publication-venue">
        Published in <i>Methods in Ecology and Evolution</i> (2025)
      </div>
      <p class="publication-summary">
        An open-source pipeline combining accelerometry, 1D convolutional neural networks, class rebalancing, temporal smoothing, and conformal prediction for uncertainty-aware behavior classification.
      </p>
      <div class="publication-links">
        <a href="https://www.biorxiv.org/content/10.1101/2024.12.28.630628v2.full.pdf">[Paper]</a>
        <a href="/projects/AWD-Biologging/">[Project Page]</a>
        <a href="https://github.com/medhaaga/AWD-Biologging">[Code]</a>
        <a href="https://zenodo.org/records/16890491">[Dataset]</a>
      </div>
    </div>
  </div>

</div>
