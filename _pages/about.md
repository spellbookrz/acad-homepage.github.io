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
I am a Ph.D. candidate at the Institute of Metal Forming (IBF), RWTH Aachen University (2023.10–present), supervised by <a href="https://www.ibf.rwth-aachen.de/cms/IBF/Das-Institut/Team/Das-IBF/Erweiterte-Institutsleitung/~bgbozz/Sebastian-Muenstermann/">Prof. Dr.-Ing. Sebastian Münstermann</a>.
My research focuses on fatigue and fracture mechanics, with an emphasis on integrating machine learning and multiscale modeling for damage-tolerant design.

I received my master's degree in Vehicle Engineering from the State Key Laboratory of Rail Transit Vehicle System, Southwest Jiaotong University (SWJTU), supervised by <a href="https://faculty.swjtu.edu.cn/yangbing1/zh_CN/index.htm">Prof. Bing Yang</a> and <a href="https://faculty.swjtu.edu.cn/xiaoshoune/zh_CN/index.htm">Prof. Shoune Xiao</a> (2020–2023).
I earned my bachelor’s degree in Engineering Mechanics from the School of Mechanics and Aerospace Engineering, SWJTU (2016–2020).

My current research covers two major directions in damage-tolerant fatigue and fracture analysis:

1. **Physics-embedded Machine Learning for Fatigue and Fracture**

   I incorporate physical information and domain knowledge into machine learning models to accurately predict crack initiation, crack propagation, and fatigue life. Representative works have been published in

   <a href="https://doi.org/10.1016/j.engfracmech.2025.111136">Engineering Fracture Mechanics</a>

   <a href="https://link.springer.com/article/10.1007/s12540-024-01628-6">Metals and Materials International</a>

   <a href="https://link.springer.com/article/10.1186/s10033-023-00876-8">Chinese Journal of Mechanical Engineering</a>

   <a href="http://ysxb.csu.edu.cn/thesisDetails#10.11817/j.ysxb.1004.0609.2022-43508&lang=zh">中国有色金属学报 (Chinese Journal of Nonferrous Metals)</a>

2. **Crystal Plasticity Finite Element Method (CPFEM)**

   I employ CPFEM to systematically investigate microstructure-sensitive fatigue crack initiation and growth in metallic materials. Representative work has been published in

   <a href="https://doi.org/10.1016/j.ijfatigue.2025.109302">International Journal of Fatigue</a> 

I am aiming to integrate these two research directions to develop data-driven multiscale frameworks for understanding and predicting fatigue behavior.


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 My second paper during Ph.D study for a microstructure-sensitive fatigue modeling by CPFEM is published in <a href="https://doi.org/10.1016/j.ijfatigue.2025.109302">International Journal of Fatigue</a>.
- *2025.05*: &nbsp;🎉🎉 I cooperate with <a href="https://www.researchgate.net/profile/Feng-Feng-11">Feng Feng</a> for predicting the probability fatigue life of AM materials in <a href="https://doi.org/10.1016/j.eswa.2025.127098">Expert Systems with Applications</a>.
- *2025.04*: &nbsp;🎉🎉 My first paper during Ph.D study for a general PINN framework for fatigue life prediction is published in <a href="https://doi.org/10.1016/j.engfracmech.2025.111136">Engineering Fracture Mechanics</a>.
- *2025.02*: &nbsp;🎉🎉 I cooperate with <a href="https://www.researchgate.net/profile/Liao-Zhen">Prof. Zhen Liao</a> for crack propagation mechanisms in AM Al-Mg alloy in <a href="https://doi.org/10.1016/j.msea.2025.147802">Materials Science and Engineering: A</a>.
- *2024.12*: &nbsp;🎉🎉 I cooperate with <a href="https://www.researchgate.net/profile/Shuancheng-Wang">Shuancheng Wang</a> for evaluating SIFs by symbolic regression in <a href="https://doi.org/10.1016/j.engfracmech.2024.110641">Engineering Fracture Mechanics</a>.
- *2024.11*: &nbsp;🎉🎉 I cooperate with Feng Feng (<a href="https://www.researchgate.net/profile/Feng-Feng-11">link</a>) for predicting fatigue life of SLM316L steel by PINN in <a href="https://doi.org/10.1016/j.ijfatigue.2024.108486">International Journal of Fatigue</a>.
- *2024.08*: &nbsp;🎉🎉 I cooperate with Shuancheng Wang (<a href="https://www.researchgate.net/profile/Shuancheng-Wang">link</a>) for effect of stress ratio and overload on fatigue crack growth behaviour in <a href="https://doi.org/10.1016/j.engfracmech.2024.110210">Engineering Fracture Mechanics</a>.
- *2024.01*: &nbsp;🎉🎉 I publish my last paper from my master's study for modeling fatigue short crack growth behavior in <a href="https://link.springer.com/article/10.1007/s12540-024-01628-6">Metals and Materials International</a>.
- *2023.10*: &nbsp;🎉🎉 I start my Ph.D research at RWTH Aachen University in Germany.
- *2023.09*: &nbsp;🎉🎉 I cooperate with <a href="https://www.researchgate.net/profile/Shuancheng-Wang">Shuancheng Wang</a> for mixed mode crack growth behaviour of EA4T steel in <a href="https://doi.org/10.1016/j.engfracmech.2023.109430">Engineering Fracture Mechanics</a>.
- *2023.06*: &nbsp;🎉🎉 I receive my master's degree from Southwest Jiaotong University.

# 📝 Publications 

- **Shuwei Zhou**, Mian Huang, Christian Häffner, Sophie Stebner, Min Cai, Zhichao Wei, Bing Yang, Sebastian Münstermann (2026) "Microstructure-sensitive crystal plasticity and fatigue indicator modeling for LZ50 steel" International Journal of Fatigue, 203, 109302. DOI: [10.1016/j.ijfatigue.2025.109302](https://doi.org/10.1016/j.ijfatigue.2025.109302)

- Feng Feng, Tao Zhu, Bing Yang, Zhe Zhang, **Shuwei Zhou**, Shoune Xiao (2025) "Probabilistic fatigue life prediction in additive manufacturing materials with a physics-informed neural network framework" Expert Systems with Applications, 275, 127098. DOI: [10.1016/j.eswa.2025.127098](https://doi.org/10.1016/j.eswa.2025.127098)

- **Shuwei Zhou**, Manuel Henrich, Zhichao Wei, Feng Feng, Bing Yang, Sebastian Münstermann (2025) "A general physics-informed neural network framework for fatigue life prediction of metallic materials" Engineering Fracture Mechanics, 322, 111136. DOI: [10.1016/j.engfracmech.2025.111136](https://doi.org/10.1016/j.engfracmech.2025.111136)

- Shuancheng Wang, **Shuwei Zhou**, Bing Yang, Shoune Xiao, Guangwu Yang, Tao Zhu (2024) "Effective stress intensity factor range for fatigue cracks propagating in mixed mode I-II loading" Engineering Fracture Mechanics, 312, 110641. DOI: [10.1016/j.engfracmech.2024.110641](https://doi.org/10.1016/j.engfracmech.2024.110641)

- Shuancheng Wang, Bing Yang, **Shuwei Zhou**, Yuanzhi Wang, Shoune Xiao (2024) "Effect of stress ratio and overload on mixed-mode crack propagation behaviour of EA4T steel" Engineering Fracture Mechanics, 306, 110210. DOI: [10.1016/j.engfracmech.2024.110210](https://doi.org/10.1016/j.engfracmech.2024.110210)

- Shuancheng Wang, Bing Yang, **Shuwei Zhou**, Jian Li, Shoune Xiao (2024) "Closure Effect of I + II Mixed-mode Crack for EA4T Axle Steel" Chinese Journal of Mechanical Engineering, 37(1). DOI: [10.1186/s10033-024-01061-1](https://doi.org/10.1186/s10033-024-01061-1)

- Feng Feng, Tao Zhu, Bing Yang, **Shuwei Zhou**, Shoune Xiao (2024) "A physics-informed neural network approach for predicting fatigue life of SLM 316L stainless steel based on defect features" International Journal of Fatigue, 188, 108486. DOI: [10.1016/j.ijfatigue.2024.108486](https://doi.org/10.1016/j.ijfatigue.2024.108486)

- **Shuwei Zhou**, Bing Yang, Shoune Xiao, Guangwu Yang, Tao Zhu (2024) "Interpretable Machine Learning Method for Modelling Fatigue Short Crack Growth Behaviour" Metals and Materials International, 30(7), 1944-1964. DOI: [10.1007/s12540-024-01628-6](https://doi.org/10.1007/s12540-024-01628-6)  

- **Shuwei Zhou**, Bing Yang, Shoune Xiao, Guangwu Yang, Tao Zhu (2023) "Crack Growth Rate Model Derived from Domain Knowledge-Guided Symbolic Regression" Chinese Journal of Mechanical Engineering, 36(1). DOI: [10.1186/s10033-023-00876-8](https://doi.org/10.1186/s10033-023-00876-8)

- **Shuwei Zhou**, Bing Yang, Chao Wang, Shuancheng Wang, Shoune Xiao, Guangwu Yang, Tao Zhu (2023) "Estimation fatigue crack growth rate of 6005A–T6 aluminum alloys with different stress ratios using machine learning methods/机器学习法预测不同应力比 6005A-T6铝合金疲劳裂纹扩展速率" 中国有色金属学报 (Chinese Journal of Nonferrous Metals), 33(8), 2416-2427. DOI: [10.11817/j.ysxb.1004.0609.2022-43508](http://ysxb.csu.edu.cn/thesisDetails#10.11817/j.ysxb.1004.0609.2022-43508&lang=zh)

- Shuancheng Wang, Bing Yang, Jian Li, **Shuwei Zhou**, Shoune Xiao (2023) "Mixed mode crack growth behaviour considering plasticity-induced and roughness-induced closure" Engineering Fracture Mechanics, 289, 109430. DOI: [10.1016/j.engfracmech.2023.109430](https://doi.org/10.1016/j.engfracmech.2023.109430)

- Bing Yang, Zhanjiang Wei, Zhen Liao, **Shuwei Zhou**, Shoune Xiao, Tao Zhu, Guangwu Yang, Mingmeng Wang (2021) "Optimisation Method for Determination of Crack Tip Position Based on Gauss-Newton Iterative Technique" Chinese Journal of Mechanical Engineering, 34(1). DOI: [10.1186/s10033-021-00585-0](https://doi.org/10.1186/s10033-021-00585-0)


# 📖 Educations
- *2023.10 - present*, Ph.D. candidate in the Institute of Metal Forming, RWTH Aachen University, Germany.
- *2020.09 - 2023.06*, Master's degree in Vehicle Engineering, State Key Laboratory of Rail Transit Vehicle System, Southwest Jiaotong University, China.
- *2016.09 - 2020.06*, Bachelor's degree in Engineering Mechanics, School of Mechanics and Aerospace Engineering, Southwest Jiaotong University, China.


# 💻 Reviewer
Journal: Reliability Engineering & System Safety, Engineering Structures, Engineering Fracture Mechanics, Theoretical and Applied Fracture Mechanics, Engineering Applications of Artificial Intelligence, Journal of Materials Research and Technology, Structural and Health Monitoring, International Journal of Pressure Vessels and Piping, 工程热物理学报 (Journal of Engineering Thermophysics).
