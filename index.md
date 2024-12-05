---
title: Home
nav:
  order: 0
  tooltip:  Homepage, brief introduction
---

# 实验室简介

ADMIS实验室依托于同济大学计算机科学与技术学院，专注于生物信息、复杂网络系统、多模态智能技术以及时空数据挖掘等前沿领域研究。实验室汇聚了一支兼具深厚学术底蕴与丰富实战经验的精英团队，秉持着对基础研究的执着追求与跨学科合作的开放态度，矢志不渝地推动科技创新，攻克行业难题。

近年来，ADMIS实验室在科研征途上成果丰硕，不仅深化了理论基础研究，更在海洋环境监测、基层社会治理现代化、药物分子创新发现、智能制造等多个实际应用场景取得了突破性成就，已成为推动相关领域发展的重要力量。

我们诚挚邀请对上述研究方向感兴趣、矢志科研探索的同学加入我们的团队，共同开启智慧与创新的非凡旅程，携手为科技进步与社会发展贡献力量。

# About ADMIS

The ADMIS Lab, affiliated with the School of Computer Science and Technology at Tongji University, focuses on cutting-edge research in bioinformatics, complex network systems, multimodal intelligent technologies, and spatiotemporal data mining. The lab brings together a team of elite researchers with a solid academic foundation and extensive practical experience. With a commitment to foundational research and an open attitude towards interdisciplinary collaboration, the ADMIS Lab is dedicated to driving technological innovation and tackling industry challenges.

In recent years, the lab has achieved remarkable results, advancing both theoretical research and practical applications in areas such as marine environmental monitoring, modernization of grassroots social governance, drug molecular discovery, and intelligent manufacturing. It has become a significant force in advancing these fields.

We warmly invite students interested in the above research directions and passionate about scientific exploration to join our team. Together, we will embark on an extraordinary journey of wisdom and innovation, contributing to technological progress and societal development.


{% include section.html %}

## 最新动态
{% assign recent_news = site.posts | sort: "date" | reverse | slice: 0 %}
{% for news in recent_news %}
  {%
    include post-excerpt.html
    affiliation=news.affiliation
    author=news.author
    authors=news.authors
    buttons=news.buttons
    caption=news.caption
    content=news.content
    date=news.date
    description=news.description
    excerpt=news.excerpt
    height=news.height
    icon=news.icon
    id=news.id
    image=news.image
    last_modified_at=news.last_modified_at
    link=news.link
    lookup=news.lookup
    name=news.name
    publisher=news.publisher
    repo=news.repo
    role=news.role
    slug=news.slug
    style=news.style
    subtitle=news.subtitle
    tags=news.tags
    text=news.text
    title=news.title
    tooltip=news.tooltip
    type=news.type
    url=news.url
    width=news.width
  %}
{% endfor %}

**<a href='./news'>See more...</a>**

## 研究方向

{% capture text %}

生物信息学方向包括单细胞测序数据分析和药物分子数据分析两个子方向。单细胞测序数据分析主要聚焦于scRNA-seq和scATAC-seq数据的处理与分析，例如去批次效应、聚类、数据插补、分化轨迹推断、调控网络构建等。药物分子数据分析主要聚焦于药物分子性质预测与药物分子从头设计，旨在加速药物研发过程，设计满足性质需求的理想新药物分子。

课题组近年来一直在探索单细胞多组学测序数据融合方法及其在医学领域的应用，用于发现新的调控机制、调控靶点以及细胞微环境影响等。此外，课题组也在探索药物分子数据分析的新方法，在药物分子表示、药物分子性质预测、药物-靶点相互作用预测、药物-疾病相互作用预测等问题上取得了良好的进展。

{% endcapture %}

{%
  include feature.html
  image="images/research/bioinfo.jpg"
  title="生物信息学"
  text=text
%}

{% capture text %}

时空数据挖掘(Spatio-Temporal Data Mining, STDM)旨在分析同时具有时间和空间特性的数据，并基于分析结果解决生产和生活中的各类问题。ADMIS团队长期研究高稀疏时空数据补全、广域时空精准预测、鲁棒性时空异常检测、时空因果分析等问题，提出了一系列时空数据分析创新方法，有效挖掘时空数据中的深层次模式和规律，提高时空数据质量和时空数据分析的准确性。

研究成果服务于智慧海洋、智能交通、城市治理、自然灾害监测、生态环境保护等领域。

{% endcapture %}

{%
  include feature.html
  image="images/research/stdm.png"
  title="时空数据挖掘"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

多模态智能技术(Multimodal Intelligence Technology, MIT)旨在解决图像、文本、语音、视频等不同模态数据融合分析过程中存在的模态异构、信息不对称、噪声干扰大、语义对齐困难的关键技术难题。

ADMIS团队重点研究多模态数据检索和多模态数据融合两大任务，提出了基于多模态数据、知识图谱和大模型的多模态数据智能分析技术，为情感分析、图像分类、图文检索、目标检测等各类应用提供了有效的解决方案，并广泛应用于社会治理、智慧城市、产业分析、智能制造等领域。


{% endcapture %}

{%
  include feature.html
  image="images/research/multimodal.jpg"
  title="多模态智能技术"
  text=text
%}

{% capture text %}

图结构数据在自然界和人类社会中广泛存在。作为一种独立的数据模态，它在多模态数据融合中始终扮演着麻烦制造者的角色，如何表征、对齐、融合、补全、增强图结构数据，理解拓扑的演化规律及其对个体间相互作用的影响是目前学术界和工业界共同关注的研究热点。

ADMIS-网络组研究图神经网络架构改进与任务适配、检索增强的大语言模型生成、多模态数据匹配与融合、信息传播建模、级联预测、锚链预测、合作演化、链路及其权重预测、加权网络建模与随机扩散，服务于舆情监控、个性化推荐、关键人物跟踪、地产估价、城市防灾等领域。

{% endcapture %}

{%
  include feature.html
  image="images/research/graph.jpg"
  title="图数据挖掘"
  flip=true
  style="bare"
  text=text
%}
