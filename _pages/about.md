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

<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="site-nav" class="greedy-nav">
        <button><div class="navicon"></div></button>
        <ul class="visible-links">
          <li class="masthead__menu-item masthead__menu-item--lg masthead__menu-home-item"><a href="#about-me">Homepage</a></li>
          <li class="masthead__menu-item"><a href="/#about-me">About Me</a></li>
            <li class="masthead__menu-item"><a href="/#-news">News</a></li>
            <li class="masthead__menu-item"><a href="/#-publications">Publications</a></li>
            <li class="masthead__menu-item"><a href="/#-honors-and-awards">Honors and Awards</a></li>
            <li class="masthead__menu-item"><a href="/#-educations">Educations</a></li>
            <li class="masthead__menu-item"><a href="/#-invited-talks">Invited Talks</a></li>
            <li class="masthead__menu-item"><a href="/#-internships">Internships</a></li>
        </ul>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>
       
<p><span class="anchor" id="about-me"></span></p>

<p>I graduated with a Master of Science degree in computer vision and machine learning from the Australian National University in 2021. Currently, I am pursuing a Ph.D. at the Australian National University’s College of Engineering and Computer Science in Canberra, ACT, Australia, with a focus on computer vision and machine learning. My research aims to explore and advance the intersection of computer vision and natural language processing, particularly in the context of Vision Large Language Models (VLLMs). I have developed a Set-of-Vision prompting (SoV) approach to enhance zero-shot emotion recognition by integrating spatial information, such as facial landmarks and bounding boxes, to improve face detection accuracy and emotion categorization. This work has the potential to significantly improve emotion recognition systems in natural environments, opening up new avenues for VLLMs in real-world applications.</p>
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<h1 id="-news">🔥 News</h1>
<ul>
  <li><em>2024.11</em>:  🎉🎉 The paper titled "Visual Prompting in LLMs for Enhancing Emotion Recognition" has been published in EMNLP 2024.</li>
  <li><em>2024.06</em>:  🎉🎉 The paper titled "LLDif: Diffusion Models for Low-light Emotion Recognition" has been published in ICPR 2024.</li>
</ul> 

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📝 Publications  -->
<h1 id="-publications">📝 Publications</h1>
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">EMNLP 2024</div><img src="images/emnlp_2024.png" alt="sym" width="100%" /></div></div>
<div class="paper-box-text">

    <p><a href="https://aclanthology.org/2024.emnlp-main.257.pdf">Visual Prompting in LLMs for Enhancing Emotion Recognition</a></p>

    <p> <strong> Qixuan Zhang, Zhifeng Wang,</strong> Dylan Zhang, Wenjia Niu,
      Sabrina Caldwell, Tom Gedeon, Yang Liu, Zhenyue Qin, EMNLP 2024</p>

    <p><a href="https://wangzhifengharrison.github.io/sov_prompts_emnlp/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>Proposed Set-of-Vision (SoV) prompting approach for enhancing facial expression recognition in Vision-Language Large Models (VLLMs).
      </li>
    </ul>
  </div>
</div>
<!-- 2 paper -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICPR 2024</div><img src="images/icpr_2024.jpg" alt="sym" width="100%" /></div></div>
<div class="paper-box-text">

    <p><a href="https://link.springer.com/chapter/10.1007/978-3-031-78201-5_25">LLDif: Diffusion Models for Low-light Emotion Recognition</a></p>

    <p> <strong> Zhifeng Wang</strong>, Kaihao Zhang & Ramesh Sankaranarayana, ICPR 2024 </p>

    <!-- <p><a href="https://wangzhifengharrison.github.io/sov_prompts_emnlp/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>Proposed Set-of-Vision (SoV) prompting approach for enhancing facial expression recognition in Vision-Language Large Models (VLLMs).
      </li>
    </ul> -->
  </div>
</div>

<!-- 3 paper -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Neurocomputing 2024</div><img src="images/handpose.jpg" alt="sym" width="100%" /></div></div>
<div class="paper-box-text">

    <p><a href="https://www.sciencedirect.com/science/article/pii/S0925231224014528">DM-HAP: Diffusion model for accurate hand pose prediction</a></p>

    <p> <strong> Zhifeng Wang</strong>, Kaihao Zhang , Ramesh Sankaranarayana, Neurocomputing 2024 </p>

    <!-- <p><a href="https://wangzhifengharrison.github.io/sov_prompts_emnlp/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>Proposed Set-of-Vision (SoV) prompting approach for enhancing facial expression recognition in Vision-Language Large Models (VLLMs).
      </li>
    </ul> -->
  </div>
</div>

<!-- 4 paper -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ICIP 2024</div><img src="images/lrdif_icip.jpg" alt="sym" width="100%" /></div></div>
<div class="paper-box-text">

    <p><a href="https://arxiv.org/pdf/2402.00250">LRDif: Diffusion Models for Under-Display Camera Emotion Recognition
      </a></p>

    <p> <strong> Zhifeng Wang</strong>, Kaihao Zhang , Ramesh Sankaranarayana, ICIP 2024 </p>

    <!-- <p><a href="https://wangzhifengharrison.github.io/sov_prompts_emnlp/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>Proposed Set-of-Vision (SoV) prompting approach for enhancing facial expression recognition in Vision-Language Large Models (VLLMs).
      </li>
    </ul> -->
  </div>
</div>

<!-- 5 paper -->
<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Neurocomputing 2023</div><img src="images/micro-architecture.png" alt="sym" width="100%" /></div></div>
<div class="paper-box-text">

    <p><a href="https://www.sciencedirect.com/science/article/pii/S0925231224009676">Htnet for micro-expression recognition
      </a></p>

    <p> <strong> Zhifeng Wang</strong>, Kaihao Zhang , Ramesh Sankaranarayana, Neurocomputing 2023 </p>

    <!-- <p><a href="https://wangzhifengharrison.github.io/sov_prompts_emnlp/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>Proposed Set-of-Vision (SoV) prompting approach for enhancing facial expression recognition in Vision-Language Large Models (VLLMs).
      </li>
    </ul> -->
  </div>
</div>
<!-- 6 paper -->
<ul>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10428424">Geometric-Aware Facial Landmark Emotion Recognition</a>, Qixuan Zhang, <strong>Zhifeng Wang </strong> , Yang Liu, Zhenyue Qin, Kaihao Zhang, Tom Gedeon, <strong>CSECS 2023</strong></li>
</ul>
<!-- 7 paper -->
<ul>
  <li><a href="https://arxiv.org/abs/2404.13493">Authentic Emotion Mapping: Benchmarking Facial Expressions in Real News</a>, Qixuan Zhang, <strong>Zhifeng Wang </strong> , Yang Liu, Zhenyue Qin, Kaihao Zhang, Sabrina Caldwell, Tom Gedeon, <strong></strong></li>
</ul>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<h1 id="-educations">📖 Educations</h1>
<ul>
  <li><em>2022.03 - 2025.01 (now)</em>, Ph.D. at the Australian National University’s College of Engineering and Computer Science in Canberra, ACT, Australia.</li>
  <li><em>2020.02 - 2022.02</em>,M.S. degree in computer vision and machine learning from the Australian National University.</li>
</ul> 
<!-- 
# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<h1 id="-invited-talks">💬 Invited Talks</h1>
<ul>
  <li><em>2024.10</em>, SoV Prompting: Enhancing Vision Large Language Models for Zero-Shot Emotion Recognition with Spatial Visual Prompts, in ANU AI Talk</li>
  <li><em>2024.06</em>,  A diffusion-based framework for enhancing facial expression recognition in extremely low-light environments through label-aware embeddings and transformer networks, ANU HDR Talk </li>
  <li><em>2023.04</em>, A diffusion-based framework leveraging transformers for robust facial expression recognition under under-display camera (UDC) challenges. </li>
  <!-- <li><em>2023.04</em>, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  | <a href="https://github.com/">[video]</a></li> -->
  <li><em>2022.04</em>, A novel approach for micro-expression recognition leveraging local and global facial feature interactions to enhance performance. </li>
</ul> 
<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
<!-- 
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->