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

# Publications 

<div class="publications-grid">

  <div class="pub-item">
    <div class="pub-image">
      <div class="conf-badge">NeurIPS 2025</div>
      <img src="/images/POTT.png" alt="POTT Method">
    </div>
    <div class="pub-content">
      <h3 class="pub-title">A Physics-preserved Transfer Learning Method for Differential Equations</h3>
      <p class="pub-authors"><strong>Hao-Ran Yang</strong>, Chuan-Xian Ren</p>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2505.01281" class="pub-link">Paper</a>
        <a href="#" class="pub-link">Poster</a>
        <a href="#" class="pub-link">Code</a>
      </div>
    </div>
  </div>


  <div class="pub-item">
    <div class="pub-image">
      <div class="conf-badge">NeurIPS 2025</div>
      <img src="/images/GLSGE.png" alt="GLSGE Method">
    </div>
    <div class="pub-content">
      <h3 class="pub-title">A Generalized Label Shift Perspective for Cross-Domain Gaze Estimation</h3>
      <p class="pub-authors"><strong>Hao-Ran Yang</strong>, Xiaohui Chen, Chuan-Xian Ren</p>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2505.13043" class="pub-link">Paper</a>
        <a href="#" class="pub-link">Poster</a>
        <a href="#" class="pub-link">Code</a>
      </div>
    </div>
  </div>


  <div class="pub-item">
    <div class="pub-image">
      <div class="conf-badge">ECCV 2024 <span class="oral-tag">oral</span></div>
      <img src="/images/COD.png" alt="COD Method">
    </div>
    <div class="pub-content">
      <h3 class="pub-title">COD: Learning Conditional Invariant Representation for Domain Adaptation Regression</h3>
      <p class="pub-authors"><strong>Hao-Ran Yang</strong>, Chuan-Xian Ren, You-Wei Luo</p>
      <div class="pub-links">
        <a href="https://arxiv.org/pdf/2408.06638" class="pub-link">Paper</a>
        <a href="#" class="pub-link">Poster</a>
        <a href="#" class="pub-link">Code</a>
      </div>
    </div>
  </div>

</div>

<style>
.publications-grid {
  display: flex;
  flex-direction: column;
  gap: 2.5rem;
  margin: 2rem 0;
}

.pub-item {
  display: flex;
  gap: 2rem;
  align-items: flex-start;
  padding: 1.5rem;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 2px 12px rgba(0,0,0,0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.pub-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(0,0,0,0.12);
}

.pub-image {
  flex-shrink: 0;
  width: 220px;
  text-align: center;
}

.conf-badge {
  background: linear-gradient(135deg, #2c3e50, #34495e);
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 6px;
  font-size: 0.9rem;
  font-weight: 600;
  margin-bottom: 1rem;
  display: inline-block;
}

.oral-tag {
  background: #e74c3c;
  color: white;
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  font-size: 0.8rem;
  margin-left: 0.5rem;
  font-weight: 600;
}

.pub-image img {
  width: 100%;
  max-width: 200px;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.pub-image img:hover {
  transform: scale(1.02);
}

.pub-content {
  flex: 1;
  min-width: 0; 
}

.pub-title {
  font-size: 1.2rem;
  font-weight: 600;
  color: #2c3e50;
  margin: 0 0 0.8rem 0;
  line-height: 1.4;
}

.pub-authors {
  color: #7f8c8d;
  font-size: 1rem;
  margin: 0 0 1.2rem 0;
  line-height: 1.5;
}

.pub-links {
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

.pub-link {
  display: inline-block;
  padding: 0.5rem 1.2rem;
  background: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-size: 0.9rem;
  font-weight: 500;
  transition: all 0.2s ease;
}

.pub-link:hover {
  background: #2980b9;
  transform: translateY(-1px);
  box-shadow: 0 2px 8px rgba(52, 152, 219, 0.3);
}

.pub-link:first-child {
  background: #e74c3c;
}

.pub-link:first-child:hover {
  background: #c0392b;
}

@media (max-width: 768px) {
  .pub-item {
    flex-direction: column;
    text-align: center;
    gap: 1.5rem;
  }
  
  .pub-image {
    width: 100%;
  }
  
  .pub-image img {
    max-width: 250px;
  }
  
  .pub-links {
    justify-content: center;
  }
}

@media (max-width: 480px) {
  .pub-item {
    padding: 1rem;
  }
  
  .pub-title {
    font-size: 1.1rem;
  }
  
  .pub-links {
    gap: 0.5rem;
  }
  
  .pub-link {
    padding: 0.4rem 1rem;
    font-size: 0.85rem;
  }
}
</style>


# Honors and Awards
- *2023.09*.&nbsp; First Prize of Outstanding Student Scholarship of Sun Yat-sen University
- *2023.08*.&nbsp; Eight place of Chinese Student Orienteering Championship, Men's Group A

# Educations
- *2023.09 - 2026.06 (now)*,&nbsp; M.S. in School of Mathematics, Sun Yat-Sen University
- *2019.09 - 2023.06*,&nbsp; B.S. in School of Mathematics, Sun Yat-Sen University

# Talks
- *2024.10*.&nbsp; Oral presentation at ECCV 2024, Milano

# Reviewer
- PRCV 2024, 2025
