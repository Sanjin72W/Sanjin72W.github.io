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

I am currently a student majoring in Automation (UWA Joint Program) at the School of Computer Science, Southwest University in Chongqing, China.Ranking 4/102 students([[Link]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/ranking_222022321132054_2025-04-02.pdf)) with a GPA of 4.3/5([[Link]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/GPA_222022321132054_2025-04-02.pdf)) and working in the Multimedia Digital Technology Laboratory under the supervision of Prof. Xiaoqin Tang[[Link]](https://cis.swu.edu.cn/info/1014/4462.htm).

My research primarily focuses on 2D/3D CT reconstruction and MRI reconstruction. I am proficient in PyTorch and C, and also experienced in MATLAB. I have a solid understanding of the fundamental frameworks behind algorithms such as diffusion models and 3DGS, with particularly deep insights into the NeRF framework.


My research interest includes: 
- Biomedical image reconstruction 
- Accelerate INR


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Our paper has been accepted by MICCAI2025.
- *2025.05*: &nbsp;🎉🎉 Participant, 2025 China Conference on Image and Graphics.[[Link]](https://raw.githubusercontent.com/Sanjin72W/Sanjin72W.github.io/main/images/confere.png)
- *2025.03*: &nbsp;🎉🎉 Our paper has been submitted to ICCV. 


# 📝 Publications 

### Due to the conference's double-blind review requirements, the experimental methods have been concealed and noise has been added to the experimental results.
---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI</div><img src='images/MICCAI_Figure1.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Qinglei Cao<sup>†</sup>, <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang<sup>†</sup></span>, Xiaoqin Tang<sup>*</sup>. MICCAI2025.
-	Paper's Contribution: A coarse reconstruction is achieved within seconds by designing a CUDA-based Target Prior Estimator (TPE), and a Target Prior Structure Encoder (TPSE) is used to extract structural prior embeddings from TPE to enhance the input encoding. This leads to a qualitative breakthrough in implicit learning-based 3D cone-beam CT reconstruction under sparse-view conditions.
-	My Contribution: TPSE is designed to pre-extract structural features without relying on a trainable network.
-	[[Code]]()Coming soon.[[Paper]]()Waiting for camera-ready edition.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV</div><img src='images/ICCV_result.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Qinglei Cao<sup>†</sup>, <span style="font-size:1.2em; font-weight:bold;">Ziyao Tang<sup>†</sup></span>, Xiaoqin Tang<sup>*</sup>. ICCV.
-	Under rebuttal; scores 5–5–5 (confidences 1-3-5); decision on June 26, 2025.
-	The full paper and accompanying code will be made available upon paper acceptance.[[Preview]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/ICCV_result.pdf)

</div>
</div>

### Experimental Progress
---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">3DCT-Reconstruction</div><img src='images/Experiment1.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Ziyao Tang, Qinglei Cao, Ping Meng, Enhao Li, Xiaoqin Tang(supervisor). Accelerate INR.
-	An extension of NAF’s ray continuity supervision to enforce continuity between voxel layers along each ray, which effectively reveals an object’s internal structure in sparse-view CT.(Since 04.2025.)
-	[[Preview]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/AI.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Accelerate INR</div><img src='images/AI.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Qinglei Cao, Ziyao Tang, Xiaoqin Tang(supervisor). Accelerate INR.
-	INR Acceleration Algorithm Based on Hard Sample Selection and Gradient Grouping.(LRS Classic Hard Sample Mining Sampling Method, MLG SAX-NeRF CVPR2024 Sampling Method, Since 08.2024 - 02.2025.)
-	[[Preview]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/AI.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Frequency-domain</div><img src='images/kspace_result.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	Ziyao Tang, Ping Meng, Xiaoqin Tang(supervisor). Frequency-domain implicit reconstruction of 2D MRI images from highly undersampled k-space data.
-	Modifications were made to the network structure to effectively mitigate INR's spectral bias.(Since 02.2025 - 04.2025)
-	[[Preview]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/Kspace_result.pdf)
</div>
</div>

# 🎖 Honors and Awards
- *2025.07* National Scholarship Candidate(The final result will be released in early October).
- *2025.06* Second Prize (National-level Recommendation), China AI and Robotics Competition.[[Link]](https://github.com/)
- *2025.05* Third Prize, Chongqing Division, China University Student Computer Design Competition.[[Link]](https://github.com/)
- *2024.11* Second prize in the National Mathematical Modeling Competition for College students.[[Link]](https://github.com/)
- *2024.09* Third class scholarship to Southwest University.[[Link]](https://github.com/)
- *2024.08* Third prize of Chongqing College Students Electronic Design Competition.[[Link]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/electric_competition.pdf)
- *2023.09* `Merit student` of Southwest University.[[Link]](https://github.com/)
- *2023.09* Second class scholarship to Southwest University.[[Link]](https://github.com/)

# 📖 Educations
- *2022.09 - 2026.06 (Expected)*, Major in Automation, School of Computer Science, Southwest University(UWA Joint Program). 

# 💬 Recommendation Letter
- *Prof. Xiaoqin Tang*: My supervisor, Associate Professor，School of Computer Science, Southwest University.[[Link]](https://github.com/)[[📧]](mailto:brian.usher99@outlook.com)
- *Prof. Brian Usher*: Professor, formerly the dean of the Faculty of Engineering at La Trobe University. [[Link]](https://github.com/) [[📧]](mailto:brian.usher99@outlook.com)
- *Dr. Anwarul Patwary*: Lecturer, School of Physics, Maths and Computing, Computer Science and Software Engineering, UWA.[[Link]](https://github.com/)[[📧]](mailto:mdanwarulkaium.patwary@uwa.edu.au)
- (Feel free to contact them.)

# 💻 Internships
- *2023.07 - 2023.08*, Center for Experimental Electronic&information, Peking University.[[Link]](https://github.com/Sanjin72W/Sanjin72W.github.io/blob/main/images/PekingU.pdf)
