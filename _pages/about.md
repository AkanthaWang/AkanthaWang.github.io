---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<div class="home-showcase">
  <section class="intro-panel">
    <div class="intro-copy">
      <p class="intro-kicker">Data Science · Multimodal Learning · Affective Computing</p>
      <h1 class="intro-title">Shiyu Wang</h1>
      <p class="intro-description">I am a postgraduate student in Data Science and Engineering at East China Normal University, supervised by Prof. <a href="https://wangyanckxx.github.io/">Yan Wang</a>. My work centers on building reliable multimodal systems for emotion understanding and deepfake detection.</p>
      <div class="intro-actions">
        <a class="showcase-button primary" href="#publications">View Publications</a>
        <a class="showcase-button secondary" href="#education">Education</a>
      </div>
    </div>
    <div class="intro-aside">
      <div class="focus-card">
        <p class="focus-card-label">Current Research Focus</p>
        <div class="tag-list">
          <span class="tag-chip">Expression Recognition</span>
          <span class="tag-chip">Affective Computing</span>
          <span class="tag-chip">Embodied Intelligence</span>
          <span class="tag-chip">Deepfake Detection</span>
        </div>
      </div>
    </div>
  </section>

  <section class="showcase-section">
    <h1 id="news">🔥 News</h1>
    <ul class="timeline-list">
      <li>
        <span class="timeline-date">2024.08</span>
        <div class="timeline-body">🎉 One paper for <strong>多元软混合样本驱动的图文对齐人脸伪造检测方法</strong> was accepted by <strong>《中国图象图形学报》</strong>.</div>
      </li>
    </ul>
  </section>

  <section class="showcase-section">
    <h1 id="publications">📝 Publications</h1>
    <p class="section-intro">Selected work in deepfake detection, affective computing, and multimodal reasoning.</p>
    <p class="section-note">🧑‍💻 Equal contribution, 📮 Corresponding author</p>

    <div class="paper-box">
      <div class="paper-box-image">
        <div class="paper-media">
          <div class="badge">中国图象图形学报</div>
          <img src="images/MSB_CLIP.png" alt="Preview image for the multi-soft-blend deepfake detection paper" width="100%">
        </div>
      </div>
      <div class="paper-box-text">
        <p class="paper-status">Accepted Paper</p>
        <h2 class="paper-title">多元软混合样本驱动的图文对齐人脸伪造检测方法</h2>
        <p class="paper-authors"><strong>Shiyu Wang</strong>, Caibo Feng, Chunxiao Liu📮, Yisheng Jin</p>
        <div class="paper-links">
          <a class="paper-link paper-link-primary" href="http://cjig.ijournals.cn/jig/ch/reader/download_new_edit_content.aspx?edit_id=20240813160335001&file_no=202405050000002&journal_id=jig">
            <span class="paper-link-label">Paper</span>
            <span class="paper-link-meta">Read publication</span>
          </a>
          <a class="paper-link" href="https://github.com/AkanthaWang/MultiSoftBlend-DeepFake-Detection">
            <span class="paper-link-label">Project Page</span>
            <span class="paper-link-meta">Code and details</span>
          </a>
        </div>
      </div>
    </div>

    <div class="paper-box">
      <div class="paper-box-image">
        <div class="paper-media">
          <div class="badge">Under Review</div>
          <img src="images/InsightVQA.png" alt="Preview image for the InsightVQA benchmark project" width="100%">
        </div>
      </div>
      <div class="paper-box-text">
        <p class="paper-status">Benchmark Paper</p>
        <h2 class="paper-title">InsightVQA: High-Dimensional Emotion-Cognitive Visual Question Answering Benchmark</h2>
        <p class="paper-authors"><strong>Shiyu Wang</strong>🧑‍💻, Ziyu Liu🧑‍💻, Chaoyi Yu, Yujie Yin, Zhongqian Mao, Jing Chen, Jiaqi Song, Yunshi Lan, Yan Wang📮</p>
        <div class="paper-links">
          <a class="paper-link paper-link-primary" href="https://arxiv.org/pdf/2606.02171">
            <span class="paper-link-label">Paper</span>
            <span class="paper-link-meta">View arXiv PDF</span>
          </a>
          <a class="paper-link" href="https://akanthawang.github.io/InsightVQA/">
            <span class="paper-link-label">Project Page</span>
            <span class="paper-link-meta">Benchmark overview</span>
          </a>
        </div>
      </div>
    </div>
  </section>

  <div class="detail-grid">
    <section class="showcase-section compact-section">
      <h1 id="education">📖 Education</h1>
      <ul class="timeline-list">
        <li>
          <span class="timeline-date">2025.09 - now</span>
          <div class="timeline-body"><strong>Postgraduate</strong> in Data Science and Engineering, East China Normal University, Shanghai</div>
        </li>
        <li>
          <span class="timeline-date">2021.09 - 2025.06</span>
          <div class="timeline-body"><strong>Bachelor</strong> in Computer Science and Technology, Zhejiang Gongshang University, Hangzhou</div>
        </li>
      </ul>
    </section>

    <section class="showcase-section compact-section">
      <h1 id="awards">🎖️ Honors and Awards</h1>
      <ul class="award-list">
        <li><span class="award-year">2025</span> Zhejiang Gongshang University Outstanding Thesis</li>
        <li><span class="award-year">2025</span> Outstanding Graduate of Zhejiang Province</li>
        <li><span class="award-year">2025</span> National Scholarship for Undergraduates</li>
        <li><span class="award-year">2024</span> Second Prize in the 16th National College Student Information Security Competition</li>
        <li><span class="award-year">2024</span> Zhejiang Provincial Government Scholarship</li>
      </ul>
    </section>
  </div>
</div>
