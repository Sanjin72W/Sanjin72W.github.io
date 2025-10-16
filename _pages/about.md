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

I am currently a student majoring in Automation (University of Western Australia Joint Program) at the School of Computer And Information Science, Southwest University in Chongqing, China. Ranking 4/102 students with a GPA of 4.3/5 and working in the Multimedia Digital Technology Laboratory under the supervision of Prof. Xiaoqin Tang[[Link]](https://cis.swu.edu.cn/info/1014/4462.htm).

My research primarily focuses on 2D and 3D CT reconstruction as well as 2D MRI reconstruction. In particular, for sparse‐view CT, our work has already achieved superior imaging quality with just 12 views. I am proficient in PyTorch and C, and also experienced in MATLAB. I have developed deep insights into the NeRF framework.


My research interest includes: 
- Biomedical image reconstruction 
- Accelerate INR


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Our paper has been accepted by PRCV2025.
- *2025.08*: &nbsp;🎉🎉 Our paper has been accepted by PG2025.
- *2025.06*: &nbsp;🎉🎉 Our paper has been accepted by ICCV2025 <span style="color:red;">Highlight</span>. 
- *2025.06*: &nbsp;🎉🎉 Our paper has been accepted by MICCAI2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI2025</div><img src='images/MICCAI_Figure1.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Target Prior-enriched Implicit 3D CT Reconstruction with Adaptive Ray Sampling.
-	Qinglei Cao<sup>†</sup>, <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang<sup>†</sup></span>, Xiaoqin Tang<sup>*</sup>. MICCAI2025( CORE A / CCFB ).
-	My Contribution: The non-trainable Target Prior Structure Encoder (TPSE) extracts structural information from the Target Prior Estimator (TPE) and integrates it into the neural network’s input encoding.(The TPE, developed by my co-author, is a CUDA-based prior generator that runs in seconds and achieves slightly better results than SART-TV, which requires minutes.)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV2025</div><img src='images/ICCV_Method.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- TPG-INR: Target Prior-Guided Implicit 3D CT Reconstruction for Enhanced Sparse-view Imaging.
-	Qinglei Cao<sup>†</sup>, <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang<sup>†</sup></span>, Xiaoqin Tang<sup>*</sup>. ICCV2025 <span style="color:red;">Highlight</span> ( CORE A<sup>*</sup> / CCFA ).
-	My Contribution: Developed a vanilla version of Target Prior-guided Voxel Sampling (TPVS), which leverages target priors to avoid wasting sampling points in air regions. (My co-author further refined the theoretical framework to enable adaptive acquisition of high-frequency information; while the vanilla version primarily speeds up convergence, the optimized method also delivers significant reconstruction-quality gains for CT with over 30 views.)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PG2025</div><img src='******************' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Global-Local Complementary Representation Network for Vehicle Re-Identification.
-	Mingchen Deng, <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang</span>，Guoqiang Xiao<sup>*</sup>. PG( CORE A / CCFB ).

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV2025</div><img src='******************' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Global-Local Complementary Representation Network for Vehicle Re-Identification.
-	Yuhao Chen, Mingchen Deng，<span style="font-size:1.2em; font-weight:bold;">Ziyao Tang<sup>*</sup></span>. PG( CORE A / CCFB ).

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE-TCI</div><img src='images/IEEE_TMI.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Target-specific Prior Generation and Prior-guided INR Learning for Sparse-view and Limited-angle CBCT Reconstruction.
-	Xiaoqin Tang<sup>†</sup><sup>*</sup>(supervisor), <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang<sup>†</sup></span>，Qinglei Cao, Ping Meng, Enhao Li. IEEE-TCI( JCR Q2 ).
-	It introduces a general method for addressing sparse‐view CT and limited‐angle CT, achieving good results with only 12 projection angles.
-	Under review.

</div>
</div>

### Experimental Progress
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DCT-Reconstruction</div><img src='images/Experiment1.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	<span style="font-size:1.2em; font-weight:bold;">Ziyao Tang</span>, Qinglei Cao, Ping Meng, Enhao Li, Xiaoqin Tang(supervisor). Accelerate INR.
-	An extension of NAF’s ray continuity supervision to enforce continuity between voxel layers along each ray, which effectively reveals an object’s internal structure in sparse-view CT.(Since 04.2025.)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Accelerate INR</div><img src='images/AI.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Qinglei Cao, <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang</span>, Xiaoqin Tang(supervisor). 3D SVCT Reconstruction.
-	INR Acceleration Algorithm Based on Hard Sample Selection and Gradient Grouping.(LRS Classic Hard Sample Mining Sampling Method, MLG SAX-NeRF CVPR2024 Sampling Method, Since 08.2024 - 02.2025.)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2D MRI(AF=6) Frequency Domain</div><img src='images/kspace_result.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	<span style="font-size:1.2em; font-weight:bold;">Ziyao Tang</span>, Ping Meng, Xiaoqin Tang(supervisor). Frequency-domain implicit reconstruction of 2D MRI images from highly undersampled k-space data.
-	Fitting a K-space that exhibits rapid variations using an implicit neural network—which is inherently biased toward low‐frequency, smooth components—is not easy.(Since 02.2025 - 04.2025)
</div>
</div>

# 🎖 Honors and Awards

### Awards
---
- *2025.06* Second Prize (National-level Recommendation), China AI and Robotics Competition.
- *2025.05* Third Prize, Chongqing Division, China University Student Computer Design Competition.
- *2024.11* Second prize in the National Mathematical Modeling Competition for College students.
- *2024.08* Third prize of Chongqing College Students Electronic Design Competition.

### Honors
---
- *2025.07* National Scholarship Candidate(The final result will be released in early October).
- *2024.09* Third class scholarship to Southwest University.
- *2023.09* Perseverance and Hard Work Award of Southwest University
- *2023.09* Merit student of Southwest University.
- *2023.09* Second class scholarship to Southwest University.

# 📖 Educations
- *2022.09 - 2026.06 (Expected)*, Major in Automation, School of Computer Science, Southwest University(UWA Joint Program). 

# 💬 Recommendation Letter
- *Prof. Xiaoqin Tang*: My supervisor, Associate Professor，School of Computer Science, Southwest University. [[📧]](mailto:tangx0530@swu.edu.cn)
- *Prof. Brian Usher*: Professor, formerly the dean of the Faculty of Engineering at La Trobe University. [[📧]](mailto:brian.usher99@outlook.com)
- *Dr. Anwarul Patwary*: Lecturer, School of Physics, Maths and Computing, Computer Science and Software Engineering, UWA. [[📧]](mailto:mdanwarulkaium.patwary@uwa.edu.au)

# 💻 Internships
- *2023.07 - 2023.08*, Center for Experimental Electronic&information, Peking University.[[Link]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/PekingU.pdf)
