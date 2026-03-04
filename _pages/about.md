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

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">👨‍🏫 关于我</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

本人的主要研究方向包括**机器学习**与**数据科学**的**通用方法研究与行业应用**，研究课题包括：**[异质数据机器学习]** **[弱/无监督联邦学习]** **[非稳态数据分析]** 以及大语言模型在上述领域和行业中的应用。已在相关领域顶级期刊和会议如**TPAMI, TNNLS, TIP, TMM, TCYB, SIGMOD, SIGKDD, NeurIPS, CVPR, ICCV, AAAI, IJCAI, ACM MM**等发表论文90余篇。

<!--
<a href='https://scholar.google.com/citations?user=EnqM5F4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
<a href='https://scholar.google.com/citations?user=EnqM5F4AAAAJ' target='_blank'><img src="https://img.shields.io/badge/citations-805-9cf?logo=Google%20Scholar&labelColor=f6f6f6&style=flat"></a>
-->

主持**国家自然科学基金2项**（2024、2021）和省部级科研项目5项，入选广东特支计划（青年拔尖人才，2026）和深圳市高层次人才奖励计划（C类，2016-2021）。现担任SCI期刊*IEEE Transactions on Emerging Topics in Computational Intelligence*（TETCI）副主编（Associate Editor）。在学术和人才培养方面获得多项荣誉，含广东**省科技进步二等奖**（2023），**最佳论文奖**（Springer ISMIS’18，IEEE CIS Competition'20, IEEE DOCS'24），教育部-华为“智能基座”先锋教师称号等。

<span style="color: #0b5394;">
🎉🎉本人的开放环境机器学习课题组（Open-environment Machine learning Group, 简称OMG）长期招收和培养对科学研究感兴趣的保研生、考研生、本科科研生（招生详情和课题组简介见<a href="/zh-OMG/"><strong>关于OMG</strong></a>）。
</span>

<span class='anchor' id="news"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">🔥 新闻</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

- *2026/02*: &nbsp;🎉🎉 两篇论文被**CVPR 2026**录用，恭喜刘赫昭和侯世豪同学、以及卢杨教授！
- *2026/01*: &nbsp;🎉 一篇论文被**DASFAA 2026**录用为长文，恭喜陈俊仰同学！
- *2026/01*: &nbsp;🎉 两篇论文被**ICASSP 2026**录用，恭喜邱淑洁和陈泰熙同学！
- *2026/01*: &nbsp;🎉🎉 论文“[Learning Self-Growth Maps for…](https://ieeexplore.ieee.org/abstract/document/11007519)”（TNNLS 2025）入选ESI高被引。
- *2025/12*: &nbsp;🎉 两篇论文被**IoTJ**接收。
  
  ... ... 查看历史新闻请点[这里](/zh-news/) ... ...

<span class='anchor' id="publications"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">📝 论文</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">异质数据机器学习</div><img src='images/Het-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **异质特征数据表征学习**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.09049)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'24</span>](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)
<!--
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IJCAI'22</span>](https://www.ijcai.org/proceedings/2022/522)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ESWA'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0957417425003604)
-->
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'23</span>](https://ieeexplore.ieee.org/abstract/document/9887970)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span>](https://ieeexplore.ieee.org/abstract/document/9346004)

- **异质特征数据距离度量**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGMOD'26</span>](https://dl.acm.org/doi/abs/10.1145/3769772)
<!--
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICASSP'25</span>](https://ieeexplore.ieee.org/abstract/document/10889806)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'24</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA240709)
-->
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'22</span>](https://ieeexplore.ieee.org/abstract/document/9079460)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'20</span>](https://ieeexplore.ieee.org/abstract/document/8671525)

- **异质分布样本聚类分析**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
<!--
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICDCS'24</span>](https://ieeexplore.ieee.org/abstract/document/10631083)
-->
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://ieeexplore.ieee.org/abstract/document/11300877)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/11007519)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'25</span>](https://ieeexplore.ieee.org/abstract/document/11134305)
<!--
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'18</span>](https://ieeexplore.ieee.org/abstract/document/8423698)
-->
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">弱/无监督联邦学习</div><img src='images/Fed-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **联邦聚类分析**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
DOCS'24</span>](https://ieeexplore.ieee.org/abstract/document/10704350)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://ieeexplore.ieee.org/abstract/document/11328086)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
INS'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0020025525010941)

- **异构联邦学习**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
CVPR'26</span>](xxx)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
CVPR'25</span>](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mind_the_Gap_Confidence_Discrepancy_Can_Guide_Federated_Semi-Supervised_Learning_CVPR_2025_paper.html)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'25</span>](https://ebooks.iospress.nl/volumearticle/75876)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/10373104)

  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">非稳态数据分析</div><img src='images/NSD-Analysis.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **时序数据分析**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.17008)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
BIBM'25</span>](https://arxiv.org/abs/2510.12214)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'23</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA230625)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
PRICAI'25</span>](https://arxiv.org/abs/2510.15985)

- **流数据/概念漂移分析**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'26</span>](https://ieeexplore.ieee.org/abstract/document/11134305)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/11007519)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
  
</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">大语言模型应用</div><img src='images/Het-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **大语言模型提示调谐**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.09049)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'24</span>](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IJCAI'22</span>](https://www.ijcai.org/proceedings/2022/522)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ESWA'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0957417425003604)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'23</span>](https://ieeexplore.ieee.org/abstract/document/9887970)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span>](https://ieeexplore.ieee.org/abstract/document/9346004)

- **大语言模型表征增强**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGMOD'26</span>](https://dl.acm.org/doi/abs/10.1145/3769772)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICASSP'25</span>](https://ieeexplore.ieee.org/abstract/document/10889806)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'24</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA240709)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'22</span>](https://ieeexplore.ieee.org/abstract/document/9079460)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'20</span>](https://ieeexplore.ieee.org/abstract/document/8671525)

- **大语言模型综述**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICDCS'24</span>](https://ieeexplore.ieee.org/abstract/document/10631083)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://ieeexplore.ieee.org/abstract/document/11300877)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/11007519)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'25</span>](https://ieeexplore.ieee.org/abstract/document/11134305)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'18</span>](https://ieeexplore.ieee.org/abstract/document/8423698)
  
</div>
</div>
-->
<br>
**代表性论文列表**

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGMOD'26</span> 
[Categorical Data Clustering via Value Order Estimated Distance Metric Learning](https://dl.acm.org/doi/abs/10.1145/3769772)<br>
**Yiqun Zhang**, Mingjie Zhao, Hong Jia, Mengke Li, Yang Lu and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
CVPR'26</span> 
SECOS: Semantic Capture for Rigorous Classification in Open-World Semi-Supervised Learning<br>
Hezhao Liu, Jiacheng Yang, Junlong Gao, Mengke Li, **Yiqun Zhang**, Shreyank Gowda and Yang Lu<sup>&#x2709;</sup>

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
AAAI'26</span> 
[Mask the Redundancy: Evolving Masking Representation Learning for Multivariate Time-Series Clustering](https://arxiv.org/abs/2511.17008)<br>
Zexi Tan, Xiaopeng Luo, Yunlin Liu and **Yiqun Zhang**<sup>&#x2709;</sup>

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGKDD'24</span> 
[QGRL: Quaternion Graph Representation Learning for Heterogeneous Feature Data Clustering](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)<br>
Junyang Chen, Yuzhu Ji, Rong Zou, **Yiqun Zhang**<sup>&#x2709;</sup> and Yiu-ming Cheung

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
NeurIPS'24</span> 
[Improving Visual Prompt Tuning by Gaussian Neighborhood Minimization for Long-Tailed Visual Recognition](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bc667ac84ef58f2b5022da97a465cbab-Abstract-Conference.html)<br>
Mengke Li, Ye Liu, Yang Lu, **Yiqun Zhang**, Yiu-ming Cheung and Hui Huang<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TMM'26</span> 
[NIDC: General Task Backbone for Neuroimaging Analysis via Interpretable Deep Clustering](https://ieeexplore.ieee.org/abstract/document/11353921/)<br>
Jiayu Ye, An Zeng<sup>&#x2709;</sup>, Dan Pan, Junhao Chen, Jingliang Zhao, **Yiqun Zhang** and Yang Liu

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TAI'25</span> 
[Trending Applications of Large Language Models: A User Perspective Survey](https://ieeexplore.ieee.org/abstract/document/11199892)<br>
**Yiqun Zhang**, Mingjie Zhao, Yunfan Zhang and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span> 
[Online Heterogeneous Feature Selection](https://ieeexplore.ieee.org/abstract/document/11274409)<br>
**Yiqun Zhang**, Xinxi Chen, Lang Zhao, Yuzhu Ji, Peng Liu and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span> 
[Learning Self-Growth Maps for Fast and Accurate Imbalanced Streaming Data Clustering](https://ieeexplore.ieee.org/abstract/document/11007519)<br>
**Yiqun Zhang**, Sen Feng, Pengkai Wang, Zexi Tan, Xiaopeng Luo, Yuzhu Ji, Rong Zou and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span> 
[Learnable Weighting of Intra-attribute Distances for Categorical Data Clustering with Nominal and Ordinal Attributes](https://ieeexplore.ieee.org/abstract/document/9346004)<br>
**Yiqun Zhang** and Yiu-ming Cheung<sup>&#x2709;</sup>

  ... ... 完整论文列表请点[这里](/zh-publications/)或访问：[DBLP](https://dblp.org/pid/125/5587-6.html) &#124; [谷歌学术](https://scholar.google.com/citations?user=EnqM5F4AAAAJ&hl=zh-CN) ... ...

<span class='anchor' id="honors-and-awards"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">🏆 荣誉与获奖</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

<!-- 
- *2026/02*: IEEE汇刊TETCI优秀编委
-->
- *2026/01*: 广东工业大学优秀研究生导师
- *2025/12*: 广东工业大学学报优秀编委
- *2024/12*: ACM SIGKDD 2025 Excellent Reviewer
- *2024/08*: 2023年度广东省科技进步二等奖
- *2024/08*: IEEE第6届复杂系统数据驱动优化国际会议（DOCS 2024）最佳论文奖
- *2022/09*: 教育部-华为智能基座先锋教师称号
- *2021/06*: 广东工业大学计算机学院青年教师教学竞赛院赛一等奖（仅设一名）
- *2019/12*: 香港浸会大学计算机科学系Research Performance Award
- *2019/08*: IEEE智能计算学会（香港）研究论文竞赛冠军
- *2018/10*: Springer第24届国际智能系统方法研讨会（ISMIS 2018）最佳学生论文奖
- *2014/06*: 香港浸会大学计算机科学系学业优秀奖学金
- *2014/01*: 香港浸会大学计算机科学系学业优秀奖学金


<span class='anchor' id="educations"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">👨‍🎓 教育背景</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

- *2014/09 - 2019/11*: 香港浸会大学，计算机科学系，哲学博士（导师：张晓明教授，长江学者，IEEE Fellow，AAAS Fellow，IAPR Fellow）
- *2013/09 - 2014/11*: 香港浸会大学，计算机科学系，理学硕士
- *2009/09 - 2013/07*: 华南理工大学，生物医学工程系，工学学士
- *2006/09 - 2009/07*: 深圳市红岭中学，理科班

<span class='anchor' id="invited-talks"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">💬 特邀报告</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

- *2025/12*: 山西大学，动态环境复杂分布数据聚类分析
- *2024/12*: 东北大学/流程工业综合自动化全国重点实验室， Clustering Complex Data Under Dynamic Environment
- *2024/12*: 广东工业大学，动态环境下的复杂数据聚类分析
- *2023/11*: 南方科技大学，Learning from Complex Data with Cross-Coupled Heterogeneous Attributes
- *2021/04*: 广东工业大学，以投稿和审稿人视角浅谈人工智能科研

<span class='anchor' id="internships"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">💻 工作经历</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 140px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

- *2026/01 至今*: 广东工业大学，计算机学院，特聘教授
- *2024/12 - 2025/12*: 香港浸会大学，计算机科学系，访问研究学者
- *2023/12 - 2026/01*: 广东工业大学，计算机学院，副教授
- *2022/09 - 2023/12*: 广东工业大学，计算机学院，特聘副教授
- *2020/10 - 2022/09*: 广东工业大学，计算机学院，讲师
- *2019/09 - 2021/02*: 香港浸会大学，计算机科学系，博士后
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<div style="margin-top: 60px;">
  
  <div style="height: 1px; background: linear-gradient(to right, transparent, #cbd5e1, transparent);"></div>

  <div style="background: linear-gradient(to right, transparent, rgba(241, 245, 249, 0.8), transparent); padding: 40px 0 30px 0;">
    
    <div style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 50px;">
      
      <div style="text-align: left; line-height: 1.8;">
        
        <div style="font-weight: bold; font-size: 1.1em; margin-bottom: 5px; color: #4b5563;">
          📊 访问统计
        </div>
        
        <div style="color: #64748b; font-size: 0.9em;">
          <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
          <span id="busuanzi_container_site_pv" style="display:none;">
            👀 本站总访问量: <span id="busuanzi_value_site_pv" style="font-weight: bold; color: #475569;"></span> 次
          </span>
        </div>
        
        <div style="color: #94a3b8; font-size: 0.85em; margin-top: 2px;">
          © {{ site.time | date: "%Y" }} 张逸群. All rights reserved.<br>
          最后更新：{{ site.time | date: "%Y年%m月" }}
        </div>
        
      </div>

      <div style="width: 100px; opacity: 0.9;"> 
        <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=lPtt2sUwH1MwEnQW4pcHVaruKWdriQxF0N9KIeqgnws"></script>
      </div>

    </div>
  </div>
</div>





