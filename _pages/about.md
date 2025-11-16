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
I am a Ph.D. candidate at the Institute of Metal Forming (IBF), RWTH Aachen University (2023.10–present), supervised by (<a href="https://www.ibf.rwth-aachen.de/cms/IBF/Das-Institut/Team/Das-IBF/Erweiterte-Institutsleitung/~bgbozz/Sebastian-Muenstermann/">link</a>)Prof. Dr.-Ing. Sebastian Münstermann</a>.
My research focuses on fatigue and fracture mechanics, with an emphasis on integrating machine learning and multiscale modeling for damage-tolerant design.

I received his master's degree in Vehicle Engineering from the State Key Laboratory of Rail Transit Vehicle System, Southwest Jiaotong University (SWJTU), supervised by (<a href="https://faculty.swjtu.edu.cn/yangbing1/zh_CN/index.htm">link</a>)Prof. Bing Yang</a> and (<a href="https://faculty.swjtu.edu.cn/xiaoshoune/zh_CN/index.htm">link</a>)Prof. Shoune Xiao</a> (2020–2023).
I earned my bachelor’s degree in Engineering Mechanics from the School of Mechanics and Aerospace Engineering, SWJTU (2016–2020).

My current research covers two major directions in damage-tolerant fatigue and fracture analysis:

Physics-embedded Machine Learning for Fatigue and Fracture
I incorporate physical information and domain knowledge into machine learning models to accurately predict crack initiation, crack propagation, and fatigue life. Representative works have been published in

<a href="https://doi.org/10.1016/j.engfracmech.2025.111136">Engineering Fracture Mechanics</a> 
<a href="https://link.springer.com/article/10.1007/s12540-024-01628-6">Metals and Materials International</a> 

<a href="https://link.springer.com/article/10.1186/s10033-023-00876-8">Chinese Journal of Mechanical Engineering</a> 

<a href="http://ysxb.csu.edu.cn/thesisDetails#10.11817/j.ysxb.1004.0609.2022-43508&lang=zh">中国有色金属学报 (Chinese Journal of Nonferrous Metals)</a> 

Crystal Plasticity Finite Element Method (CPFEM)
I employ CPFEM to systematically investigate microstructure-sensitive fatigue crack initiation and growth in metallic materials. Representative work has been published in

<a href="https://doi.org/10.1016/j.ijfatigue.2025.109302">International Journal of Fatigue</a> 

I am aiming to integrate these two research directions to develop data-driven multiscale frameworks for understanding and predicting fatigue behavior.


# 🔥 News
- *2025.9*: &nbsp;🎉🎉 My second paper during Ph.D study for a microstructure-sensitive fatigue modelling by CPFEM is published in <a href="https://doi.org/10.1016/j.ijfatigue.2025.109302">International Journal of Fatigue</a> (<a href="https://doi.org/10.1016/j.ijfatigue.2025.109302">link</a>).
- *2025.5*: &nbsp;🎉🎉 I cooperate with (<a href="https://www.researchgate.net/profile/Feng-Feng-11">link</a>)Feng Feng</a> for predicting the probability fatigue life of AM materials in <a href="https://doi.org/10.1016/j.eswa.2025.127098">Expert Systems with Applications</a> (<a href="https://doi.org/10.1016/j.eswa.2025.127098">link</a>).
- *2025.04*: &nbsp;🎉🎉 My first paper during Ph.D study for a general PINN framework for fatigue life prediction is published in <a href="https://doi.org/10.1016/j.engfracmech.2025.111136">Engineering Fracture Mechanics</a> (<a href="https://doi.org/10.1016/j.engfracmech.2025.111136">link</a>).
- *2025.02*: &nbsp;🎉🎉 I cooperate with (<a href="https://www.researchgate.net/profile/Liao-Zhen">link</a>)Prof. Zhen Liao</a> for crack propagation mechanisms in AM Al-Mg alloy in <a href="https://doi.org/10.1016/j.msea.2025.147802">Materials Science and Engineering: A</a> (<a href="https://doi.org/10.1016/j.msea.2025.147802">link</a>).
- *2024.12*: &nbsp;🎉🎉 I cooperate with (<a href="https://www.researchgate.net/profile/Shuancheng-Wang">link</a>)Shuancheng Wang</a> for evaluating SIFs by symbolic regression in <a href="https://doi.org/10.1016/j.engfracmech.2024.110641">Engineering Fracture Mechanics</a> (<a href="https://doi.org/10.10
- *2024.01*: &nbsp;🎉🎉 I publish my last paper from master's study for modelling fatigue short crack growth behavior in <a href="https://link.springer.com/article/10.1007/s12540-024-01628-6">Metal Materials International</a> (<a href="https://link.springer.com/article/10.1007/s12540-024-01628-6">link</a>).
- *2023.10*: &nbsp;🎉🎉 I start my Ph.D research in RWTH Aachen University in Germany.
- *2023.09*: &nbsp;🎉🎉 I cooperate with (<a href="https://www.researchgate.net/profile/Shuancheng-Wang">link</a>)Shuancheng Wang</a> for mixed mode crack growth behaviour of EA4T steel in <a href="https://doi.org/10.1016/j.engfracmech.2023.109430">Engineering Fracture Mechanics</a> (<a href="https://doi.org/10.1016/j.engfracmech.2023.109430">link</a>).
- *2023.06*: &nbsp;🎉🎉 I receive my master's degree from Southwest Jiaotong University.

# 📝 Publications 

- **Shuwei Zhou**, Mian Huang, Christian Häffner, Sophie Stebner, Min Cai, Zhichao Wei, Bing Yang, Sebastian Münstermann (2026) "Microstructure-sensitive crystal plasticity and fatigue indicator modeling for LZ50 steel" International Journal of Fatigue, DOI: [10.1016/j.ijfatigue.2025.109302](https://doi.org/10.1016/j.ijfatigue.2025.109302)

- Feng Feng, Tao Zhu, Bing Yang, Zhe Zhang, **Shuwei Zhou**, Shoune Xiao (2025) "Probabilistic fatigue life prediction in additive manufacturing materials with a physics-informed neural network framework" Expert Systems with Applications, DOI: [10.1016/j.eswa.2025.127098](https://doi.org/10.1016/j.eswa.2025.127098)

- **Shuwei Zhou**, Manuel Henrich, Zhichao Wei, Feng Feng, Bing Yang, Sebastian Münstermann (2025) "A general physics-informed neural network framework for fatigue life prediction of metallic materials" Engineering Fracture Mechanics, DOI: [10.1016/j.engfracmech.2025.111136](https://doi.org/10.1016/j.engfracmech.2025.111136)

- Shuancheng Wang, **Shuwei Zhou**, Bing Yang, Shoune Xiao, Guangwu Yang, Tao Zhu (2024) "Effective stress intensity factor range for fatigue cracks propagating in mixed mode I-II loading" Engineering Fracture Mechanics, DOI: [10.1016/j.engfracmech.2024.110641](https://doi.org/10.1016/j.engfracmech.2024.110641)

- Shuancheng Wang, Bing Yang, **Shuwei Zhou**, Yuanzhi Wang, Shoune Xiao (2024) "Effect of stress ratio and overload on mixed-mode crack propagation behaviour of EA4T steel" Engineering Fracture Mechanics, DOI: [10.1016/j.engfracmech.2024.110210](https://doi.org/10.1016/j.engfracmech.2024.110210)

- Shuancheng Wang, Bing Yang, **Shuwei Zhou**, Jian Li, Shoune Xiao (2024) "Closure Effect of I + II Mixed-mode Crack for EA4T Axle Steel" Chinese Journal of Mechanical Engineering, DOI: [10.1186/s10033-024-01061-1](https://doi.org/10.1186/s10033-024-01061-1)

- Feng Feng, Tao Zhu, Bing Yang, **Shuwei Zhou**, Shoune Xiao (2024) "A physics-informed neural network approach for predicting fatigue life of SLM 316L stainless steel based on defect features" International Journal of Fatigue, DOI: [10.1016/j.ijfatigue.2024.108486](https://doi.org/10.1016/j.ijfatigue.2024.108486)

- **Shuwei Zhou**, Bing Yang, Shoune Xiao, Guangwu Yang, Tao Zhu (2024) "Interpretable Machine Learning Method for Modelling Fatigue Short Crack Growth Behaviour" Metals and Materials International, DOI: [10.1007/s12540-024-01628-6](https://doi.org/10.1007/s12540-024-01628-6)

- **Shuwei Zhou**, Bing Yang, Shoune Xiao, Guangwu Yang, Tao Zhu (2023) "Crack Growth Rate Model Derived from Domain Knowledge-Guided Symbolic Regression" Chinese Journal of Mechanical Engineering, DOI: [10.1186/s10033-023-00876-8](https://doi.org/10.1186/s10033-023-00876-8)

- Shuancheng Wang, Bing Yang, Jian Li, **Shuwei Zhou**, Shoune Xiao (2023) "Mixed mode crack growth behaviour considering plasticity-induced and roughness-induced closure" Engineering Fracture Mechanics, DOI: [10.1016/j.engfracmech.2023.109430](https://doi.org/10.1016/j.engfracmech.2023.109430)

- Bing Yang, Zhanjiang Wei, Zhen Liao, **Shuwei Zhou**, Shoune Xiao, Tao Zhu, Guangwu Yang, Mingmeng Wang (2021) "Optimisation Method for Determination of Crack Tip Position Based on Gauss-Newton Iterative Technique" Chinese Journal of Mechanical Engineering, DOI: [10.1186/s10033-021-00585-0](https://doi.org/10.1186/s10033-021-00585-0)


# 📖 Educations
- *2023.10 - present*, Ph.D. candidate in Institute of Metal Forming, RWTH Aachen University, Germany.
- *2020.09 - 2023.06*, Master's degree in Vehicle Engineering, State Key Laboratory of Rail Transit Vehicle System, Southwest Jiaotong University, China.
- *2016.09 - 2020.06*, Bachelor's degree in Engineering Mechanics, School of Mechanics and Aerospace Engineering, Southwest Jiaotong University, China.


# 💻 Reviewer
Journal: Reliability Engineering & System Safety, Engineering Structures, Engineering Fracture Mechanics, Theoretical and Applied Fracture Mechanics, Engineering Applications of Artificial Intelligence, Journal of Materials Research and Technology, Structural and Health Monitoring, International Journal of Pressure Vessels and Piping, 工程热物理学报.