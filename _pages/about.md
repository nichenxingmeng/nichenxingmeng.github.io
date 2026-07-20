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

<div style="text-align: justify;" markdown="1">

I am a first-year PhD student at the [Institute for Computer Science, Artificial Intelligence and Technology (INSAIT)](https://insait.ai/), advised by [Prof. Luc Van Gool](https://scholar.google.com/citations?user=TwMib_QAAAAJ&hl=en) and [Dr. Jinjin Gu](https://www.jasongt.com/). Prior to joining INSAIT, I worked as a Research Assistant at the Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences, advised by [Prof. Chao Dong](https://scholar.google.com/citations?user=OSDCB0UAAAAJ&hl=zh-en).

I received my M.S. in Computer Technology from the University of Chinese Academy of Sciences in 2025, under the supervision of [Prof. Xinfeng Zhang](https://people.ucas.ac.cn/~csxfzhang), and worked closely with [Prof. Ruiqin Xiong](https://scholar.google.com/citations?user=46Rur-YAAAAJ&hl=en) of Peking University. During my Master's, I was also fortunate to be supervised by [Dr. Li Zhang](https://scholar.google.com/citations?user=8G5-2OMAAAAJ&hl=en) and to collaborate with [Dr. Shijie Zhao](https://www.linkedin.com/in/shijie-zhao-bb017a110/) at ByteDance Inc. Earlier, I earned my B.E. in Mechanical Design, Manufacture, and its Automation from Tongji University in 2022.

My research focuses on **low-level vision**, including image/video generation, super-resolution, and restoration.

</div>

# 🔥 News
- *2026.09*: &nbsp;🎉 One paper on omnidirectional image super-resolution is accepted by **ECCV 2026**.
- *2026.02*: &nbsp;🎉 One paper on omnidirectional video super-resolution is accepted by **AAAI 2026**.

# 📝 Publications 

<style>
.pub-table td { border: none; padding: 6px 10px; }
.pub-table td p { margin: 0; }
.pub-table p { margin: 0 0 12px 0; }
</style>

<table class="pub-table" style="border-collapse:collapse;">
<tr>
<td width="180" style="vertical-align:middle; padding:6px 10px 6px 0;"><img src="images/publications/pub_d2r2osr.png" style="width:170px; height:90px; object-fit:contain;"></td>
<td style="vertical-align:top;" markdown="1">
**D²R²OSR: Degradation-Disentangled Representation for Real-World Omnidirectional Image Super-Resolution**
<br>
**Hongyu An**, Xinfeng Zhang, Xu Fan, Shijie Zhao, Li Zhang, Ruiqin Xiong
<br>
*European Conference on Computer Vision (ECCV)*, 2026 · [**Paper**](https://arxiv.org/abs/2606.29314) | [**Code**](https://github.com/nichenxingmeng/D2R2OSR)
</td>
</tr>

<tr>
<td width="180" style="vertical-align:middle; padding:6px 10px 6px 0;"><img src="images/publications/pub_stdan.png" style="width:170px; height:90px; object-fit:contain;"></td>
<td style="vertical-align:top;" markdown="1">
**Spatio-Temporal Distortion Aware Omnidirectional Video Super-Resolution**
<br>
**Hongyu An**, Xinfeng Zhang, Shijie Zhao, Li Zhang, Ruiqin Xiong
<br>
*AAAI Conference on Artificial Intelligence (AAAI)*, 2026 · [**Paper**](https://arxiv.org/abs/2410.11506) | [**Code**](https://github.com/nichenxingmeng/STDAN)
</td>
</tr>

<tr>
<td width="180" style="vertical-align:middle; padding:6px 10px 6px 0;"><img src="images/publications/pub_sdatc.png" style="width:170px; height:90px; object-fit:contain;"></td>
<td style="vertical-align:top;" markdown="1">
**Spatial Degradation-Aware and Temporal Consistent Diffusion Model for Compressed Video Super-Resolution**
<br>
**Hongyu An**, Xinfeng Zhang, Shijie Zhao, Li Zhang, Ruiqin Xiong
<br>
*arXiv preprint arXiv:2502.07381*, 2025 · [**Paper**](https://arxiv.org/abs/2502.07381)
</td>
</tr>

<tr>
<td width="180" style="vertical-align:middle; padding:6px 10px 6px 0;"><img src="images/publications/pub_fato.png" style="width:170px; height:90px; object-fit:contain;"></td>
<td style="vertical-align:top;" markdown="1">
**FATO: Frequency Attention Transformer for Omnidirectional Image Super-Resolution**
<br>
**Hongyu An**, Xinfeng Zhang, Shijie Zhao, Li Zhang
<br>
*ACM International Conference on Multimedia in Asia (MMAsia)*, 2024 · [**Paper**](https://dl.acm.org/doi/full/10.1145/3696409.3700232)
</td>
</tr>

<tr>
<td width="180" style="vertical-align:middle; padding:6px 10px 6px 0;"><img src="images/publications/pub_icip.png" style="width:170px; height:90px; object-fit:contain;"></td>
<td style="vertical-align:top;" markdown="1">
**Perception-Oriented Omnidirectional Image Super-Resolution Based on Transformer Network**
<br>
**Hongyu An**, Xinfeng Zhang
<br>
*IEEE International Conference on Image Processing (ICIP)*, 2023 · [**Paper**](https://ieeexplore.ieee.org/document/10222760)
</td>
</tr>
</table>

---

<div class="pub-table" markdown="1">

**SANR: Scene-Aware Neural Representation for Light Field Image Compression with Rate-Distortion Optimization**
<br>
Gai Zhang, Xinfeng Zhang, Lv Tang, **Hongyu An**, Li Zhang, Qingming Huang
<br>
*IEEE Transactions on Multimedia*, 2026 · [**Paper**](https://arxiv.org/abs/2510.15775)

**Enhancing Diagnostic Safety with Low Iodine, Low Radiation CTPA Classification Using Deep Learning**
<br>
Mingyao Hong, Tao Gu, **Hongyu An**, Xu Fan, Xinfeng Zhang
<br>
*Scientific Reports*, 2026 · [**Paper**](https://www.nature.com/articles/s41598-026-38223-1)

**Position: Evaluation of Visual Processing Should Be Human-Centered, Not Metric-Centered**
<br>
Jinfan Hu, Fanghua Yu, Zhiyuan You, Xiang Yin, **Hongyu An**, Xinqi Lin, Chao Dong, Jinjin Gu
<br>
*arXiv preprint arXiv:2603.00643*, 2026 · [**Paper**](https://arxiv.org/abs/2603.00643)

**Expanded SPAN for Efficient Super-Resolution**
<br>
Qing Wang, Yang Wang, **Hongyu An**, Yi Liu, Liou Zhang, Shijie Zhao
<br>
*Proceedings of the Computer Vision and Pattern Recognition Conference (CVPR Workshop)*, 2025 · [**Paper**](https://openaccess.thecvf.com/content/CVPR2025W/NTIRE/html/Wang_Expanded_SPAN_for_Efficient_Super-Resolution_CVPRW_2025_paper.html)

</div>

# 🏆 Competitions
- CVPR Workshops & NTIRE 2024 Challenge on Image Super-Resolution (×4), **3rd**.
- CVPR Workshops & NTIRE 2025 Challenge on Efficient Super-Resolution runtime sub-track, **3rd**.

# 🎖️ Honors and Awards
- Excellent Student Scholarship of Tongji University, 2019, 2020, 2021.
- Outstanding Student Scholarship of University of Chinese Academy of Sciences, 2022.
- National Scholarship, 2024.

# 📖 Educations
- Bachelor of Engineering in Mechanical Design, Manufacture, and its Automation, Tongji University, *2018.09 - 2022.07*.
- Master of Computer Technology, University of Chinese Academy of Sciences, *2022.09 - 2025.07*.

# 💻 Internships
- ByteDance Inc., *2023.09 - 2025.05*.
- XPixel Group, SIAT, CAS, *2025.06 - 2026.01*.
