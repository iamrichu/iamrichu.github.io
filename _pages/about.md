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

I am a  senior algorithm engineer at Alibaba Group, where I am a member of the prestigious T-Star Talent Program within the Taobao and Tmall Group (TTG). I earned my Ph.D. from the University of Science and Technology of China (USTC, advised by [Dong Liu](https://faculty.ustc.edu.cn/dongeliu/)) and my Bachelor's degree from Xi'an Jiaotong University (XJTU).

My research focuses on Multimedia AIGC, with specific interests in:

- Post-training for Video Foundation Models.

- Reinforcement Learning (RL) applications in Diffusion Models.

- Video Completion and Synthesis.

I have published several papers in top-tier conferences and journals, including CVPR, ECCV, and TPAMI.

🔥 We are hiring! Our team is constantly looking for motivated interns. If you are interested in pushing the boundaries of generative AI, please reach out to me at: richu@mail.ustc.edu.cn.


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 [LocalDPO](https://arxiv.org/pdf/2601.04068) is accepted to CVPR 2026
- *2026.01*: &nbsp;🎉🎉 [LaCon](https://arxiv.org/abs/2305.11520) is accepted to TIP
- *2025.12*: &nbsp;🎉🎉 [StableV2V](https://ieeexplore.ieee.org/abstract/document/11272911) is accepted to TCSVT
- *2025.08*: &nbsp;🎉🎉 [DrimNeRF](https://ieeexplore.ieee.org/abstract/document/11115135) is accepted to TCSVT
- *2024.05*: &nbsp;🎉🎉 [SketchRefiner](https://ieeexplore.ieee.org/abstract/document/10533842) is accepted to TMM
- *2024.01*: &nbsp;🎉🎉 [FGT++](https://ieeexplore.ieee.org/abstract/document/10418551/) is accepted to TPAMI
- *2022.07*: &nbsp;🎉🎉 [FGT](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780072.pdf) is accepted to ECCV 2022
- *2022.02*: &nbsp;🎉🎉 [ISVI](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Inertia-Guided_Flow_Completion_and_Style_Fusion_for_Video_Inpainting_CVPR_2022_paper.pdf) is accepted to CVPR 2022

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/localdpo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mind the Generative Details: Direct Localized Detail Preference Optimization for Video Diffusion Models](https://arxiv.org/pdf/2601.04068)

Zitong Huang\*, **Kaidong Zhang\***, Yukang Ding, Chao Gao, Rui Ding, Ying Chen, Wangmeng Zuo (*equal contribution)

[\[Paper\]](https://arxiv.org/pdf/2601.04068)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

LocalDPO is an efficient post-training framework that aligns text-to-video models with human preferences by using an automated pipeline to create localized spatio-temporal preference pairs from real videos, enabling fine-grained region-aware optimization without the need for external critic models or multi-sample ranking.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2025</div><img src='images/lacon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LaCon: Late-Constraint Diffusion for Steerable Guided Image Synthesis](https://arxiv.org/abs/2305.11520)

Chang Liu, Rui Li, **Kaidong Zhang**, Xin Luo, Dong Liu

[\[Paper\]](https://arxiv.org/abs/2305.11520)
[\[Code\]](https://github.com/AlonzoLeeeooo/LCDG)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

LaCon is a flexible and efficient "late-constraint" paradigm that achieves steerable image synthesis by aligning external conditions with the internal features of pre-trained diffusion models to guide the sampling process without requiring extra modules or heavy parameter optimization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2025</div><img src='images/stablev2v.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[StableV2V: Stablizing Shape Consistency in Video-to-Video Editing](https://ieeexplore.ieee.org/abstract/document/11272911)

Chang Liu, Rui Li, **Kaidong Zhang**, Yunwei Lan, Dong Liu

[\[Paper\]](https://ieeexplore.ieee.org/abstract/document/11272911)
[\[Code\]](https://github.com/AlonzoLeeeooo/StableV2V)
[\[Project Page\]](https://alonzoleeeooo.github.io/StableV2V/)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

StableV2V presents a novel paradigm to perform video editing in a shape-consistent manner, especially handling the editing scenarios when user prompts cause significant shape changes to the edited contents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2025</div><img src='images/drim.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Drim-NeRF: Diffusion-Based Restoration for Improving Neural Radiance Fields](https://ieeexplore.ieee.org/abstract/document/11115135)

Ganlin Yang, **Kaidong Zhang**, Jingjing Fu, Dong Liu

[\[Paper\]](https://ieeexplore.ieee.org/abstract/document/11115135)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

Drim-NeRF is a diffusion-based, backbone-agnostic restoration method that treats NeRF artifacts as a specific degradation model and utilizes optical flow warping along with feature-wrapping in the VAE decoder to produce high-fidelity, multi-view consistent enhancements for complex scenes.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2024</div><img src='images/sketch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Toward interactive image inpainting via robust sketch refinement](https://ieeexplore.ieee.org/abstract/document/10533842)

Chang Liu, Shunxin Xu, Jialun Peng, **Kaidong Zhang**, Dong Liu

[\[Paper\]](https://ieeexplore.ieee.org/abstract/document/10533842)
[\[Code\]](https://github.com/AlonzoLeeeooo/SketchRefiner)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

This paper explores the guidance of sketch in image inpainting. It seperates the completion of sketch and image and designs two specialized networks for excellent image inpainting performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/fgtpp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploiting Optical Flow Guidance for Transformer-Based Video Inpainting](https://ieeexplore.ieee.org/abstract/document/10418551/)

**Kaidong Zhang**, Jialun Peng, Jingjing Fu, Dong Liu

[\[Paper\]](https://ieeexplore.ieee.org/abstract/document/10418551)
[\[Video\]](https://www.youtube.com/watch?v=cKP20WTS2xA) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

This paper investigates how to use the power of optical flows to guide the video inpainting transformer systematically. It reaches SOTA video inpainting performance against all of the previous counterparts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/fgt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Flow-Guided Transformer for Video Inpainting](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780072.pdf)

**Kaidong Zhang**, Jingjing Fu, Dong Liu

[\[Paper\]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780072.pdf)
[\[Code\]](https://github.com/hitachinsk/FGT)
[\[Video\]](https://www.youtube.com/watch?v=GGZwkpf7xwo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

FGT is the first video inpainting framework that utilizes the optical flows to influence attention calculation in transfomer for video inpainting with higher fidelity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/isvi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Inertia-guided flow completion and style fusion for video inpainting](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Inertia-Guided_Flow_Completion_and_Style_Fusion_for_Video_Inpainting_CVPR_2022_paper.pdf)

**Kaidong Zhang**, Jingjing Fu, Dong Liu

[\[Paper\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Inertia-Guided_Flow_Completion_and_Style_Fusion_for_Video_Inpainting_CVPR_2022_paper.pdf)
[\[Code\]](https://github.com/hitachinsk/ISVI)
[\[Video\]](https://www.youtube.com/watch?v=vR9GQNRqob8) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

ISVI is a novel flow-guided video inpainting system that integrates inertia into flow completion and adopts additional style correction to produce completed videos with high fidelity.
</div>
</div>

# 📝 Arxiv Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/femoral.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Dataset for Deep Learning-based Bone Structure Analyses in Total Hip Arthroplasty](https://arxiv.org/pdf/2306.04579)

**Kaidong Zhang**, Ziyang Gan, Dong Liu, Xifu Shang

[\[Paper\]](https://arxiv.org/pdf/2306.04579)
[\[Code\]](https://github.com/hitachinsk/THA)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

The researchers propose an efficient bone structure annotation pipeline that combines non-learning-based segmentation (using graph-cut and gradient-based algorithms) with active-learning-based refinement to create a large-scale, high-quality THA dataset with minimal manual labeling.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/samed.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Customized segment anything model for medical image segmentation](https://arxiv.org/pdf/2304.13785)

**Kaidong Zhang**, Dong Liu

[\[Paper\]](https://arxiv.org/pdf/2304.13785)
[\[Code\]](https://github.com/hitachinsk/SAMed)
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

SAMed is the seminal work that utilizes Segment Anything Model (SAM) in multi-organ segmentation. It achieves remarkable performance and demonstrates the feasibility of SAM in medical usage.
</div>
</div>


# 🎖 Honors and Awards
- *2022.12* Invited speaker in Youth PhD Talk-ECCV 2022, hosted by AITime.
- *2022.01* MSRA Star of Tomorrow Excellent Internship Award
- *2020.01* 2nd place (runner up) in AI+4K HDR track of the first National Artificial Intelligence Competition **(CNY 500K)**

# 📖 Educations
- *2019.09 - 2024.06*, **Ph.D.** Electronics and Information Engineering, University of Science and Technology of China, China. 
- *2015.09 - 2019.06*, **B.S.** Electronics and Information Engineering, Xi'an Jiaotong University, China.

# 💬 Invited Talks
- *2022.10*, Flow-Guided Transformer for Video Inpainting \| [\[video\]](https://course.zhidx.com/c/NDNlYWQyNmIyZjQwOTdhOWUzODM=)

# 💻 Internships
- *2020.08 - 2022.02*, Microsoft research Asia (MSRA), China, advised by [Jingjing Fu](https://scholar.google.com/citations?user=w-6C7LkAAAAJ&hl=en).
