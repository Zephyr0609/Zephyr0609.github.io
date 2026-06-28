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

Hi! I am Zeyu Ren (任泽宇), an M.S. student at the University of Melbourne, working on generative models, world models, and dense prediction (e.g., depth and surface-normal estimation).

In today's AI era, I believe writing code is no longer the hardest part of research; the harder and more valuable skill is the ability to spot the right problems, whether they surface from theory, from visualization, or from careful self-reflection. Once a problem is found, what matters is how to solve it — and how to make the solution simpler and explain it more clearly and coherently at a theoretical level. Equally important is presentation: how to convey an idea so that others can truly understand it. These are the abilities I most want to improve during my PhD. Above all I value simplicity, avoiding redundancy and over-design. I also read broadly beyond my own field, since ideas from other areas often spark new ways of thinking about my own problems.

**I am currently looking for PhD opportunities (Fall 2027) in related areas — if you think we might be a good fit, please feel free to reach out.**

# ⏳ What Am I Doing Right Now?
- **Representation latents for diffusion-based geometry estimation models.** Exploring the use of high-dimensional representations in diffusion-based geometry estimation.
- **Feed-forward world models for driving.** A fun setting we are pursuing: building a feed-forward world model for driving scenes directly from panoramic (360°) images.

# 🔥 News
- *2026.02*: &nbsp;🎉 Our paper **StereoAdapter-2** is on [arXiv](https://arxiv.org/abs/2602.16915), and we [release the code](https://github.com/AIGeeksGroup/StereoAdapter-2).
- *2026.01*: &nbsp;🎉 Our paper **AnyDepth** is on [arXiv](https://arxiv.org/abs/2601.02760), and we [release the code](https://github.com/AIGeeksGroup/AnyDepth).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/anydepth.png' alt="AnyDepth" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AnyDepth: Depth Estimation Made Easy](https://arxiv.org/abs/2601.02760)

**Zeyu Ren**\*, Zeyu Zhang\*, Wukai Li, Qingxiang Liu, Hao Tang

<span style="font-size:0.85em;">\*Equal contribution. The University of Melbourne · Peking University · Shanghai University of Engineering Science.</span>

[**Website**](https://aigeeksgroup.github.io/AnyDepth/) [**Code**](https://github.com/AIGeeksGroup/AnyDepth)

- A frozen DINOv3 encoder paired with the Simple Depth Transformer (SDT), a single-path decoder that cuts decoder parameters by 86.6–89.2% while improving the efficiency–accuracy trade-off over DPT heads.
- Two depth-specific quality scores (distribution, gradient continuity) filter training data from 584K to 369K samples while preserving accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/stereoadapter2.png' alt="StereoAdapter-2" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StereoAdapter-2: Globally Structure-Consistent Underwater Stereo Depth Estimation](https://arxiv.org/abs/2602.16915)

**Zeyu Ren**\*, Xiang Li\*, Yiran Wang\*, Zeyu Zhang\*, Hao Tang

<span style="font-size:0.85em;">\*Equal contribution. The University of Melbourne · Peking University · Australian Centre for Robotics.</span>

[**Website**](https://aigeeksgroup.github.io/StereoAdapter-2/) [**Code**](https://github.com/AIGeeksGroup/StereoAdapter-2)

- An underwater stereo framework centered on ConvSS2D for long-range, content-adaptive disparity refinement, with the synthetic UW-StereoDepth-80K dataset; improves RMSE by 17.0% (TartanAir-UW) and 7.2% (SQUID) over StereoAdapter, validated on a real BlueROV2 platform.
</div>
</div>

- [SA-CMamba: Stripe-aware CNN-Mamba Hybrid Network for Pixel-level Surface Defect Detection](https://www.sciencedirect.com/science/article/pii/S0263224125028696), W. Li, C. Wang, W. Feng, X. Wang, **Z. Ren**, J. Wang, C. Wang, Q. Lu, **Measurement 2025** (Elsevier)

# 🎖 Honors and Awards
- **RoboCup, Robot World Cup (China)**, Member of Visual Group. *2021.01 - 2021.05*
  - Acquired depth maps with a Kinect-v2 depth camera and set up ROS communication with a robot arm to realize object grasping.
  - Won the China National Second Prize, RoboCup Family Division — Open Platform.
- **China National College Students Mechanical Innovation Design Competition**, Member. *2021.09 - 2022.06*
  - Designed a robot dog with servo modules concentrated at the thigh root — driven by a parallelogram linkage — to reduce the leg's moment of inertia and servo load.
  - Won the Beijing Municipal Second Prize.

# 📖 Educations
- <img src="images/logos/buct.png" style="height:80px;width:auto;vertical-align:middle;margin-right:6px;"> *2019.09 - 2023.06*, B.Eng., Beijing University of Chemical Technology.
- <img src="images/logos/unimelb.png" style="height:80px;width:auto;vertical-align:middle;margin-right:6px;"> *<!-- TODO 起止时间 --> - now*, M.S., University of Melbourne.

# 💻 Internships
- <img src="images/logos/pku.png" style="height:80px;width:auto;vertical-align:middle;margin-right:6px;"> *2025.03 - now*, **Peking University**, Research Assistant.
  - **Generative models.** Rethinking the latent space diffusion models operate in, and how latent quality shapes downstream prediction.
  - **World models.** Looking for a more reasonable way to build feed-forward world models.
  - **Dense prediction.** Efficient zero-shot monocular depth via a single-path decoder (AnyDepth), and globally structure-consistent underwater stereo depth via selective state-space refinement (StereoAdapter-2).
- <img src="images/logos/nwpu.png" style="height:80px;width:auto;vertical-align:middle;margin-right:6px;"> *2024.05 - 2025.03*, **Northwestern Polytechnical University**, Research Assistant.
  - Proposed SDDMamba, combining the local feature extraction of CNNs with the efficient global-context modeling of Mamba to enhance hierarchical feature representation.
  - Improved and debugged Latent Diffusion model code for joint dual-task prediction of depth and normal maps, providing experience and data on the limitations of diffusion models under multi-task learning.
  - Explored mechanisms for leveraging polarization information to improve normal reconstruction, and new ways to combine optical cues with NeRF and 3D Gaussian Splatting for 3D reconstruction and fine surface-feature extraction.
- <img src="images/logos/rmit.png" style="height:80px;width:auto;vertical-align:middle;margin-right:6px;"> *2024.03 - 2024.05*, **RMIT University**, Research Assistant.
  - Studied mainstream visual interpretability methods based on Gradient-weighted Class Activation Mapping (Grad-CAM).
  - Used PyTorch to validate the feasibility of a Fisher-information-metric-based algorithm for visual interpretability tasks.

# 🛠 Academic Services
- **Conference Reviewer:** ACM MM 2026