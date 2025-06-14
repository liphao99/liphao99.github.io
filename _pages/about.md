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



 I work at Institute for Tongyi Lab <img src='../images/tongyi.png' style='width: 1.5em;'>, Alibaba Group, as a 3D vision researcher now in Hangzhou.

 I graduated from Wuhan University with a bachelor’s degree and Tsinghua University with a master's degree, advised by Prof. [Haoqian Wang](https://www.sigs.tsinghua.edu.cn/whq/). Currently, my research topic is 3D vision, with a particular focus on 3D generation and human avatar. 
 
 <!-- Click [cv](../assets/cv.pdf) for more details. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Our Paper NOVA3D is selected as ICME 2025 Best Paper Candidate and Best Student Paper Candidate.
- *2025.04*: &nbsp;🎉🎉 Celebrate! Our GitHub project [LHM](https://github.com/aigc3d/LHM) has reached 2000 stars!
- *2025.03*: &nbsp;🎉🎉 We release LHM, a feedforward large animatable human reconstruction model.
- *2025.02*: &nbsp;🎉🎉 One paper is accepted by CVPR 2025!
- *2024.07*: &nbsp;I join Tongyi Lab, Alibaba Group <img src='../images/alibaba.png' style='width: 6em;'> , as a 3D vision algorithm researcher in Hangzhou, China.
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by ECCV 2024!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/lhm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LHM: Large Animatable Human Reconstruction Model for Single Image to 3D in Seconds](https://arxiv.org/pdf/2503.10625)

Lingteng Qiu\*, Xiaodong Gu\*, **Peihao Li\***, Qi Zuo\*, Weichao Shen, Junfei Zhang, Kejie Qiu, Weihao Yuan
Guanying Chen†, Zilong Dong†, Liefeng Bo

[**Project**](https://aigc3d.github.io/projects/LHM/)\|[![Code](https://img.shields.io/github/stars/aigc3d/LHM?label=Github%20%E2%98%85&logo=github&color=C8C)](https://github.com/aigc3d/LHM)\|[![HuggingFace](https://img.shields.io/badge/🤗-HuggingFace_Space-blue)](https://huggingface.co/spaces/DyrusQZ/LHM)\|
[![ModelScope](https://img.shields.io/badge/%20ModelScope%20-Space-blue)](https://www.modelscope.cn/studios/Damo_XR_Lab/LHM) 
-  LHM reconstructs an animatable human avatar in a
 single feed-forward pass in seconds. The resulting model supports real-time rendering and pose-controlled animation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025, Best Paper Award Candidate</div><img src='images/nova3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NOVA3D: Normal Aligned Video Diffusion Model for Single Image to 3D Generation](https://arxiv.org/pdf/2506.07698)

Yuxiao Yang\*, **Peihao Li\***, Yuhong Zhang, Junzhe Lu, Xianglong He, Minghan Qin, Weitao Wang, Haoqian Wang†

-  NOVA3D unleashes geometric 3D prior from a video diffusion model to generate high-quality textured meshes from input image.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/MaQ.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Motions as Queries: One-Stage Multi-Person Holistic Human Motion Capture](https://cvpr.thecvf.com/virtual/2025/poster/32510)

Kenkun Liu\*, Yurong Fu\*, Weihao Yuan\*, Jing Lin, **Peihao Li**, Xiaodong Gu, Lingteng Qiu, Haoqian Wang, Zilong Dong, Xiaoguang Han†

- Motions as Queries integrates the detector, tracker, and human pose and shape estimator together, which can simultaneously capture the motions of all individuals in one shot.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/gs_wild.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gaussian in the Wild: 3D Gaussian Splatting for Unconstrained Image Collections](https://arxiv.org/abs/2403.15704)

Dongbin Zhang\*, Chuming Wang\*, Weitao Wang, **Peihao Li**, Minghan Qin, Haoqian Wang†

[**Project**](https://eastbeanzhang.github.io/GS-W/)
- With an unconstrained image collection input, GS-W can render novel views with appearance tuning, achieving state-of-the-art quality and faster rendering speed.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/nerfms.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NeRF-MS: Neural Radiance Fields with Multi-Sequence](https://openaccess.thecvf.com/content/ICCV2023/html/Li_NeRF-MS_Neural_Radiance_Fields_with_Multi-Sequence_ICCV_2023_paper.html)

**Peihao Li**, Shaohui Wang, Chen Yang, Bingbing Liu, Weichao Qiu†, Haoqian Wang†

[**Project**](https://nerf-ms.github.io/) 
- NeRF-MS trains neural radiance fields from multiple sequences captured by different sensors and at different times. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/nerfvs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NeRFVS: Neural Radiance Fields for Free View Synthesis via Geometry Scaffolds](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_NeRFVS_Neural_Radiance_Fields_for_Free_View_Synthesis_via_Geometry_CVPR_2023_paper.html)

Chen Yang, **Peihao Li**, Zanwei Zhou, Shanxin Yuan, Bingbing Liu, Xiaokang Yang, Weichao Qiu, Wei Shen†

-  NeRFVS significantly reduces the distortions and floaters to achieve indoor scene free view synthesis.
</div>
</div>






# 🎖 Honors and Awards
- *2023* Ordos Talent Scholarship, Tsinghua University. 
- *2020* National Scholarship, Ministry of Education of P.R. China.
- *2019* National 1st Award, [CUMCM](http://www.mcm.edu.cn/), China.

# 📖 Educations
- *2021.09 - 2024.06*, Master, Tsinghua University. 
- *2017.09 - 2021.06*, Undergraduate, Wuhan University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2022.07 - 2023.03*, Huawei, Noah’s Ark Lab, Shenzhen.
- *2020.08 - 2020.11*, Bytedance, Beijing.
