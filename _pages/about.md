---
layout: home
permalink: /
title: "Han Wang"
excerpt: "Han Wang — Ph.D. student in CPU microarchitecture and systems security"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero home-wrap" aria-labelledby="home-title">
  <p class="home-kicker">Ph.D. student <span aria-hidden="true">/</span> Southern University of Science and Technology</p>
  <h1 id="home-title">Han Wang</h1>

  <div class="home-hero-grid">
    <div class="home-hero-meta">
      <div class="home-portrait">
        <img src="{{ site.baseurl }}/images/me.jpg" alt="Han Wang" fetchpriority="high">
      </div>
      <div class="home-actions">
        <a class="home-button home-button--solid" href="{{ site.author.googlescholar }}" target="_blank" rel="noopener">Google Scholar <span aria-hidden="true">↗</span></a>
        <a class="home-button" href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener">GitHub <span aria-hidden="true">↗</span></a>
        <a class="home-button" href="{{ site.baseurl }}/publications/">All publications <span aria-hidden="true">→</span></a>
      </div>
    </div>
    <div class="home-hero-intro">
      <p class="home-lede">
        I am a Ph.D. student at the Southern University of Science and Technology (SUSTech), advised by
        <a href="https://yinqian.org/">Prof. Yinqian Zhang</a>. I received my M.Eng. (advised by Prof. Ming Tang) and B.Eng. from the School of Cyber Science and Engineering, Wuhan University.
      </p>
      <p class="home-now">
        My work explores CPU microarchitecture reverse engineering and microarchitectural side-channel vulnerabilities, with a focus on understanding modern processors and identifying security flaws.
      </p>
    </div>
  </div>
</section>

<section class="home-section home-wrap" id="publications" aria-labelledby="selected-title">
  <header class="home-section-head">
    <span class="home-section-no">01</span>
    <h2 id="selected-title">Selected Publications</h2>
  </header>

  <ol class="home-publications">
    <li class="home-publication">
      <div class="home-venue">
        <span>USENIX Security 2026</span>
      </div>
      <div>
        <h3>Charting the Cache Side-Channel Frontier: A Systematic Study of Eviction Set Construction on Apple Silicon</h3>
        <p class="home-authors"><strong>Han Wang</strong>, Yakun Wu, Yusi Feng, Yinqian Zhang</p>
        <p class="home-publication-links">
          <a href="https://www.usenix.org/conference/usenixsecurity26/presentation/wang-han" target="_blank" rel="noopener">Paper</a>
        </p>
      </div>
    </li>

    <li class="home-publication">
      <div class="home-venue">
        <span>CCS 2026</span>
      </div>
      <div>
        <h3>FrontSpec: Uncovering and Characterizing Frontend Memory Predictors on Apple M4 Processors</h3>
        <p class="home-authors"><strong>Han Wang</strong><sup>*</sup>, Yuhao Hu<sup>*</sup>, Yusi Feng, Quancheng Wang, Ke Xu, Tang Ming, Yun Chen, Zhe Wang, Chenggang Wu, Yinqian Zhang</p>
        <p class="home-publication-links">
          <a href="https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html" target="_blank" rel="noopener">Paper</a>
        </p>
      </div>
    </li>

    <li class="home-publication">
      <div class="home-venue">
        <span>DAC 2025</span>
        <span class="home-badge">Best Paper Nominee</span>
      </div>
      <div>
        <h3>ZenLeak: Practical Last-Level Cache Side-Channel Attacks on AMD Zen Processors</h3>
        <p class="home-authors"><strong>Han Wang</strong>, Ming Tang, Quancheng Wang, Ke Xu, Yinqian Zhang</p>
        <p class="home-publication-links">
          <a href="https://yinqian.org/papers/dac25b.pdf" target="_blank" rel="noopener">Paper</a>
        </p>
      </div>
    </li>

    <li class="home-publication">
      <div class="home-venue">
        <span>DATE 2024</span>
      </div>
      <div>
        <h3>Cache Bandwidth Contention Leaks Secrets</h3>
        <p class="home-authors"><strong>Han Wang</strong>, Ming Tang, Ke Xu, Quancheng Wang</p>
        <p class="home-publication-links">
          <a href="https://ieeexplore.ieee.org/abstract/document/10546529" target="_blank" rel="noopener">Paper</a>
        </p>
      </div>
    </li>
  </ol>
  <p class="home-footnote">* Co-first authors.</p>

  <a class="home-more" href="{{ site.baseurl }}/publications/">View all publications <span aria-hidden="true">→</span></a>
</section>

<section class="home-section home-wrap" id="service" aria-labelledby="service-title">
  <header class="home-section-head">
    <span class="home-section-no">02</span>
    <h2 id="service-title">Service</h2>
  </header>
  <ul class="home-list home-list--plain">
    <li>
      <div>
        <h3>CCS 2026 AEC PC</h3>
        <p>Artifact Evaluation Committee, Program Committee</p>
      </div>
    </li>
    <li>
      <div>
        <h3>The Journal of Supercomputing</h3>
        <p>Reviewer</p>
      </div>
    </li>
    <li>
      <div>
        <h3>Journal of Hardware and Systems Security</h3>
        <p>Reviewer</p>
      </div>
    </li>
  </ul>
</section>

<section class="home-section home-wrap" id="awards" aria-labelledby="awards-title">
  <header class="home-section-head">
    <span class="home-section-no">03</span>
    <h2 id="awards-title">Awards</h2>
  </header>
  <ul class="home-list">
    <li>
      <span class="home-list-label">2025</span>
      <div>
        <h3>DAC Best Paper Award Nominee</h3>
        <p>Design Automation Conference</p>
      </div>
    </li>
    <li>
      <span class="home-list-label">2025</span>
      <div>
        <h3>Lei Jun Computer Breakthrough Scholarship</h3>
        <p>Along with Ke Xu and Quancheng Wang.</p>
      </div>
    </li>
  </ul>
</section>
