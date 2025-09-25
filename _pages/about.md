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

Hi! I'm Hao-Ran Yang (officially, Haoran Yang), a third-year master's student in the School of Mathematics at Sun Yat-sen University (SYSU), where I also completed my bachelor's degree. My research interests lie in applied mathematics and machine learning. I am particularly interested in how prior knowledge can be mathematically modeled and integrated into the design, training, and adaptation of models. 

I am always open to research collaborations and internship opportunities—please feel free to drop me an email if you are interested in working with me.   

Beyond academics, I am passionate about orienteering. As a student-athlete on SYSU's orienteering team, I have represented the school in Chinese Orienteering Championship and other major competitions. I deeply enjoy the process of reading maps, exploring the unknown, and reaching checkpoints, which gives me a unique sense of freedom and accomplishment.

# 🔥 News
- *2025.09*: Two papers are accepted by NeurIPS 2025. 
- *2024.07*: One paper is accepted by ECCV 2024 as oral paper. 

# 📝 Publications 

<div class="publications-container">
  <!-- Paper 1 -->
  <div class='paper-box'>
    <div class='paper-box-image'>
      <div class="badge">NeurIPS 2025</div>
      <img src='/images/POTT.png' alt="POTT" style="max-width: 280px; height: auto;">
    </div>
    <div class='paper-box-text'>
      <p><strong><a href="https://arxiv.org/pdf/2505.01281">A Physics-preserved Transfer Learning Method for Differential Equations</a></strong></p>
      <p><strong>Hao-Ran Yang</strong>, Chuan-Xian Ren</p>
    </div>
  </div>

  <!-- Paper 2 -->
  <div class='paper-box'>
    <div class='paper-box-image'>
      <div class="badge">NeurIPS 2025</div>
      <img src='/images/GLSGE.png' alt="GLSGE" style="max-width: 280px; height: auto;">
    </div>
    <div class='paper-box-text'>
      <p><strong><a href="https://arxiv.org/pdf/2505.13043">A Generalized Label Shift Perspective for Cross-Domain Gaze Estimation</a></strong></p>
      <p><strong>Hao-Ran Yang</strong>, Xiaohui Chen, Chuan-Xian Ren</p>
    </div>
  </div>

  <!-- Paper 3 -->
  <div class='paper-box'>
    <div class='paper-box-image'>
      <div class="badge">ECCV 2024 <strong>oral</strong></div>
      <img src='/images/COD.png' alt="COD" style="max-width: 280px; height: auto;">
    </div>
    <div class='paper-box-text'>
      <p><strong><a href="https://arxiv.org/pdf/2408.06638">COD: Learning Conditional Invariant Representation for Domain Adaptation Regression</a></strong></p>
      <p><strong>Hao-Ran Yang</strong>, Chuan-Xian Ren, You-Wei Luo</p>
    </div>
  </div>
</div>

<style>
.paper-box {
  display: flex;
  margin: 2rem 0;
  padding: 1.5rem;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  background: #fafafa;
  align-items: flex-start;
  gap: 1.5rem;
}

.paper-box-image {
  flex-shrink: 0;
  text-align: center;
}

.paper-box-image img {
  border: 1px solid #ddd;
  border-radius: 4px;
  margin-top: 0.5rem;
}

.badge {
  background: #2c3e50;
  color: white;
  padding: 0.3rem 0.8rem;
  border-radius: 4px;
  font-size: 0.85rem;
  font-weight: bold;
  display: inline-block;
}

.paper-box-text {
  flex: 1;
}

.paper-box-text p {
  margin: 0.5rem 0;
}

.paper-box-text a {
  color: #2c3e50;
  text-decoration: none;
}

.paper-box-text a:hover {
  text-decoration: underline;
  color: #3498db;
}

@media (max-width: 768px) {
  .paper-box {
    flex-direction: column;
    text-align: center;
    gap: 1rem;
  }
  
  .paper-box-image img {
    max-width: 200px !important;
  }
}
</style>

# 🎖 Honors and Awards
- *2023.09* First Prize of Outstanding Student Scholarship of Sun Yat-sen University
- *2023.08* Eight place of Chinese Student Orienteering Championship, Men's Group A

# 📖 Educations
- *2023.09 - 2026.06 (now)*, M.S. in School of Mathematics, Sun Yat-Sen University
- *2019.09 - 2023.06*, B.S. in School of Mathematics, Sun Yat-Sen University
