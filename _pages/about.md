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

# 😊 About Me
My name is Kaining Zhang, a Ph.D. student at Wuhan University. My research interests mainly lie in the intersection between 3D geometry and deep learning, specifically for tasks such as image matching, large-scale visual localization, 3D scene reconstruction, etc. **Currently I am looking for a postdoctoral position to continue my research in related fields**.

# 📖 Educations
- *2023.12 - 2025.01*, visiting Ph.D. student, Computer Vision Group, University of Bern, Switzerland.
  - **Advisor: Prof. [Paolo Favaro](https://www.cvg.unibe.ch/people/favaro)**
- *2019.09 - 2024.06 (expected)*, Ph.D. student, Multi-Spectral Vision Processing Lab, Wuhan University, Wuhan, China.
  - **Advisor: Prof. [Jiayi Ma](https://sites.google.com/site/jiayima2013/jiayi-ma-\%E9\%A9\%AC\%E4\%BD\%B3\%E4\%B9\%89-professor)**
- *2015.09 - 2019.06*, B.Sc. in Electronic Information Science and Technology, Electronic Information School, Wuhan University, Wuhan, China.

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/paper/ICML2024.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Sparse-to-dense Multimodal Image Registration via Multi-Task Learning](https://openreview.net/pdf?id=q0vILV7zAw)

**Kaining Zhang**, [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ)

International Conference on Machine Learning (ICML), 2024
  
- We propose a novel matching paradigm to address the drawbacks that current multimodal image matching paradigms are facing. Experiments are conducted on several cross-modal scenarios, including visible-infrared, visible-near infrared, and GoogleEarth.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/paper/AAAI2024.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[ResMatch: Residual Attention Learning for Feature Matching](https://ojs.aaai.org/index.php/AAAI/article/view/27915)

[Yuxin Deng](https://scholar.google.com.hk/citations?user=7_sHJXwAAAAJ&hl=zh-CN), **Kaining Zhang**, [Zizhuo Li](https://scholar.google.com.hk/citations?user=bxuEALEAAAAJ&hl=zh-CN&oi=ao), [Shihua Zhang](https://scholar.google.com.hk/citations?user=7f_tYK4AAAAJ&hl=zh-CN&oi=ao), [Yansheng Li](https://scholar.google.com.hk/citations?user=wn9hc6UAAAAJ&hl=zh-CN&oi=ao), [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ)

Proceedings of the AAAI Conference on Artificial Intelligence (AAAI), 2024
  
- We take a deep look at the attention mechanism of SuperGlue and rethink cross-attention and self-attention from the perspective of traditional feature matching and filtering. Our well-designed attention approach leads to significant performance improvements on several benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2022</div><img src='images/paper/TITS2022.png' alt="sym" width="60%"></div></div>
<div class='paper-box-text' markdown="1">

[Loop Closure Detection via Bidirectional Manifold Representation Consensus](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9994239)

**Kaining Zhang**, [Zizhuo Li](https://scholar.google.com.hk/citations?user=bxuEALEAAAAJ&hl=zh-CN&oi=ao), [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ)

IEEE Transactions on Intelligent Transportation Systems (TITS), 2022
  
- This is a comprehensive extension of our ICRA 2021. We speed up our algorithm by 63% and build the incremental database via HNSW. Meanwhile, experiments are conducted on more challenging datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAS 2022</div><img src='images/paper/LMSC.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Loop Closure Detection with Reweighting NetVLAD and Local Motion and Structure Consensus](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9785936)

**Kaining Zhang**, [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ), [Junjun Jiang](https://scholar.google.com.hk/citations?hl=zh-CN&user=WNH2_rgAAAAJ)

IEEE/CAA Journal of Automatica Sinica (JAS), 2022
  
- We propose AttentionNetVLAD to extract more powerful image representation, and address feature matching via information lying on both a 2D space and an intrinsic manifold.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAS 2022</div><img src='images/paper/LPM-GC.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Loop Closure Detection via Locality Preserving Matching with Global Consensus](https://www.ieee-jas.net/en/article/doi/10.1109/JAS.2022.105926)

[Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ), **Kaining Zhang**, [Junjun Jiang](https://scholar.google.com.hk/citations?hl=zh-CN&user=WNH2_rgAAAAJ)

IEEE/CAA Journal of Automatica Sinica (JAS), 2022
  
- A simple yet surprisingly effective feature matching approach is proposed for scenes within loop closure detection tasks (e.g., scenes with repetitive structures). The algorithm can provide reliable correspondences within only a few milliseconds.  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2021</div><img src='images/paper/LAL.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Appearance-Based Loop Closure Detection via Locality-Driven Accurate Motion Field Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9457132)

**Kaining Zhang**, [Xingyu Jiang](https://scholar.google.com.hk/citations?user=h2W90MQAAAAJ&hl=zh-CN&oi=ao), [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ)

IEEE Transactions on Intelligent Transportation Systems (TITS), 2021
  
- This is a more complete version of our IROS 2021. We propose a more reasonable loss to revise the motion field, and decrease the time complexity of the algorithm from O(N^3) to O(N). Meanwhile, experiments are conducted on more challenging datasets.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2021</div><img src='images/paper/ICRA.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Appearance-based Loop Closure Detection via Bidirectional Manifold Representation Consensus](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9561704)

**Kaining Zhang**, [Zizhuo Li](https://scholar.google.com.hk/citations?user=bxuEALEAAAAJ&hl=zh-CN&oi=ao), [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ)

IEEE International Conference on Robotics and Automation (ICRA), 2021
  
- We attempt to address loop closure detection (LCD) from the semantic aspect to the geometric one. Based on this idea, the proposed LCD system can achieve satisfying results.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2021</div><img src='images/paper/IROS.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Motion Field Consensus with Locality Preservation: A Geometric Confirmation Strategy for Loop Closure Detection](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636769)

**Kaining Zhang**, [Xingyu Jiang](https://scholar.google.com.hk/citations?user=h2W90MQAAAAJ&hl=zh-CN&oi=ao), [Xiaoguang Mei](https://scholar.google.com.hk/citations?user=2rgDpugAAAAJ&hl=zh-CN&oi=ao), [Huabing Zhou](https://scholar.google.com.hk/citations?user=9JwkFBEAAAAJ&hl=zh-CN&oi=ao), [Jiayi Ma](https://scholar.google.com.hk/citations?hl=zh-CN&user=73trMQkAAAAJ)

IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2021
  
- We address feature matching in the perspective of motion field recovery, and add extra constraints to the motion field to make it more suitable for scenes within  loop closure detection. 
</div>
</div>






