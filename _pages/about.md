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

I am a postdoctoral researcher at the School of Computer Science, University of Sydney (USYD), advised by Prof. Chang Xu. I obtained my Ph.D. degree at the School of Computer Science, Wuhan University (WHU) in June 2024, under the supervision of Prof. Bo Du and Prof. Chang Xu. Before that, I received my Bachelor's degree in computer science from Wuhan University in June 2019. I was a visiting research student at the University of Sydney (USYD) from 2022 to 2023.

My research interests lie in reinforcement learning/imitation learning algorithms and their applications in robotics. In addition, I closely follow the latest developments in generative models and LLMs.

📢 Feel free to reach out if you are seeking research collaboration in the field of robotics🤖/generative models🎨/VLM🧠. 

# 🔥 News
- *2026.02*: 🎉🎉 Three papers are accepted by **CVPR 2026**.
- *2026.01*: 🎉🎉 Our paper "Action-aware Dynamic Pruning for Efficient Vision-Language-Action Manipulation" is accepted by **ICLR 2026**. [[Code]](https://github.com/chen7086/VLA-ADP)
- *2025.11*: 🎉🎉 Our paper "Rethinking Visual Token Reduction in LVLMs under Cross-modal Misalignment" is accepted by **AAAI 2026**. [[Code]](https://github.com/Ruixxxx/VisionDrop)
- *2025.09*: 🎉🎉 Our paper "[VLA-Cache](https://vla-cache.github.io): Efficient Vision-Language-Action Manipulation via Adaptive Token Caching" is accepted by **NeurIPS 2025**.
- *2025.07*: 🎉🎉 Our paper "Color Correction Meets Cross-Spectral Refinement: A Distribution-Aware Diffusion for Underwater Image Restoration" is accepted by **TMM 2025**.
- *2025.05*: 🎉🎉 Our paper "FusionSAM: Visual Multi-Modal Learning with Segment Anything Model" is accepted by **KDD 2025**.
- *2025.05*: 🎉🎉 Our paper "Position: AI Scaling: From Up to Down and Out" is accepted by **ICML 2025**.
- *2025.04*: 🎉🎉 Our paper "On Positive-Unlabeled Classification from Corrupted Data in GANs” is accepted by **TPAMI 2025**.
<!--- *2022.12*: 🎉🎉 Our project 'Robust Gait Control and Automatic Navigation for Quadruped Robot' wins the \*first\* prize of China Graduate AI Innovation Competition **(8/1174)**-->

# 📝 Selected Publications 

1.  **Yunke Wang**, Chang Xu, Tianyu Guo, Bo Du, Dacheng Tao. "On Positive-Unlabeled Classification from Corrupted Data in GANs", IEEE Transactions on Pattern Analysis and Machine Intelligence **(TPAMI)**, 2025.
<strong style="color:gray">(CCF A, Core A\*, IF=20.4)</strong>
[[Paper]](https://ieeexplore.ieee.org/document/10980032)

2. **Yunke Wang**, Yanxi Li, Chang Xu. "AI Scaling: From Up to Down and Out", In Proceedings of the 42nd International Conference on Machine Learning **(ICML)**, 2025.
<strong style="color:gray">(CCF A, Core A\*)</strong>
[[Paper]](https://www.arxiv.org/abs/2502.01677)
[[News]](https://mp.weixin.qq.com/s/utfZ-Y2USWmwdk5z1c-W4Q?scene=1) 

4. **Yunke Wang**, Minjing Dong, Yukun Zhao, Bo Du, Chang Xu. "Imitation Learning from Purified Demonstrations", In Proceedings of the 41st International Conference on Machine Learning **(ICML)**, 2024.
<strong style="color:gray">(CCF A, Core A\*)</strong>
[[Paper]](https://proceedings.mlr.press/v235/wang24m.html)
[[Code]](https://github.com/yunke-wang/dp-il)

5. **Yunke Wang**, Bo Du, Wenyuan Wang, Chang Xu. “Multi-Tailed Vision Transformer for Efficient Inference”, Neural Networks **(NN)**, 2024.
<strong style="color:gray">(CCF B, Core A, IF=6.0)</strong>
[[Paper]](https://arxiv.org/pdf/2203.01587.pdf)

6. **Yunke Wang**, Xiyu Wang, Anh-Dung Dinh, Bo Du, Chang Xu. "Learning to Schedule in Diffusion Probabilistic Models", In Proceedings of the 29th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining **(KDD)**, 2023.
<strong style="color:gray">(CCF A, Core A\*)</strong>
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3580305.3599412)

7. **Yunke Wang**, Bo Du, Chang Xu. “Unlabeled Imperfect Demonstrations in Adversarial Imitation Learning”, In Proceedings of the 37th AAAI Conference on Artificial Intelligence **(AAAI)**, 2023.
<strong style="color:gray">(CCF A, Core A\*)</strong>
[[Paper]](https://arxiv.org/pdf/2302.06271.pdf)
[[Supp]](https://github.com/yunke-wang/yunke-wang.github.io/blob/main/docs/Appendix_For_UID.pdf)
[[Code]](https://github.com/yunke-wang/UID)

8. **Yunke Wang**, Chang Xu, Bo Du. “Robust Adversarial Imitation Learning via Adaptively-Selected Demonstrations”, In Proceedings of the 30th International Joint Conference on Artificial Intelligence **(IJCAI)**, 2021.
<strong style="color:gray">(CCF A, Core A\*)</strong>
[[Paper]](https://www.ijcai.org/proceedings/2021/0434.pdf)
[[Supp]](https://github.com/yunke-wang/yunke-wang.github.io/blob/main/docs/IJCAI__21_Robust_Adversarial_Imitation_Learning_via_Adaptively_Selected_Demonstrations.pdf)
[[Code]](https://github.com/yunke-wang/SAIL)

9. **Yunke Wang**, Chang Xu, Bo Du, Honglak Lee. “Learning to Weight Imperfect Demonstrations”, In Proceedings of the 38th International Conference on Machine Learning **(ICML)**, 2021.
<strong style="color:gray">(CCF A, Core A\*)</strong>
[[Paper]](http://proceedings.mlr.press/v139/wang21aa/wang21aa.pdf)
[[Supp]](http://proceedings.mlr.press/v139/wang21aa/wang21aa-supp.pdf)
[[Code]](https://github.com/yunke-wang/WGAIL)
[[Code_Atari]](https://github.com/yunke-wang/gail_atari)

10. **Yunke Wang**, Linwei Tao, Yutian Lin, Bo Du, Chang Xu. "Visual Imitation Learning with Calibrated Contrastive Representation", Preprint, 2024.
[[Paper]](https://arxiv.org/abs/2401.11396)


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->
 
# 🎖 Honors and Awards
- *2024.06* Outstanding Graduates, Wuhan University.
- *2023.11* Academic Innovation Scholarship, Wuhan University.
- *2023.11* National Scholarship for Graduate Students, Ministry of Education. **(1%)**
- *2023.06* KDD-23 Student Travel Award, KDD.
- *2023.01* AAAI-23 Student Scholarship, AAAI. 
- *2022.12* First Prize Winner of China Graduate AI Innovation Competition.  **(8/1174)**

  Project: Robust Gait Control and Automatic Navigation for Quadruped Robot
- *2021.10* Yisheng Ph.D. Scholarship, Wuhan University. 
- *2018.08* Second Prize Winner of Chinese Collegiate Computing Competition.
- *2018.08* First Prize Winner of Chinese Collegiate Internet of Things Design Competition (TI CUP) (Central South Region).

# 📖 Educations
- *2019.09 - 2024.06*, Ph.D. in Artificial Intelligence, Wuhan University (WHU), Wuhan, China.
- *2015.09 - 2019.06*, B.Eng. in Computer Science, Wuhan University (WHU), Wuhan, China.

# 💬 Invited Talks
- *2026.02*，“Vision-Language-Action Model: Bridging the Intelligence to the Physical World” at the University of Sydney, Deep Learning Class
- *2025.11*，“Calibration of AI Models for Reliable Decision-Making”, at CommonWealth Bank of Australia, Redfern Office, USYD-CommBank Workshop.
- *2024.11*, "Policy Learning in Diffusion Models", at the University of Queensland, Brisbane City Campus, [International Workshop on Weakly Supervised Learning 2024](https://wsl-workshop.github.io/wsl24.html).
- *2023.06*, "Imitation Learning from Imperfect Demonstrations", at "DiDi" Forum for Doctoral Students.
- *2023.02*, "Dynamic Neural Network in Vision Transformer" at the University of Sydney, Deep Learning Class.
- *2021.10*, "Deep Reinforcement Learning in Autonomous Driving" at In-Driving Co Ltd.
- *2021.09*, "Imitation Learning from Imperfect Demonstrations" at Doctoral Innovation Forum on Artificial Intelligence in Central and Western China.
  
# 🫶🏼 Academic Service
- Conference Organizer: Local Arrangement Chair of [DICTA 2026](https://dicta2026.dictaconference.org).
- Workshop Organizer: Program Chair of the [Workshop on Sustainable AI for the Future Web](https://www25-sustainableai.github.io) (WSAI) on The Web Conference 2025.
- Conference Reviewer: ICML, ICLR, NeurIPS, KDD, MM, CVPR, ICCV, ECCV, AAAI, IJCAI, ICRA, IROS, ICPR.
- Journal Reviewer: Artificial Intelligence Journal, TPAMI, TIP, TKDE, TMM, TCSVT, RA-L, Neural Networks, Neurocomputing.
- Guest Lecturer: COMP/OCMP 5329, USYD GenAI Summer School 2024, USYD GenAI Winter School 2025.
- Program Coordinator: USYD GenAI Summer School 2025
