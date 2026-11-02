---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

I am **Junteng Liu**, a first-year Ph.D. candidate at the **HKUST NLP Group**, supervised by **Prof. Junxian He**. I graduated from **Shanghai Jiao Tong University (SJTU)** in June 2024, where I was also advised by Prof. Junxian He during my undergraduate studies.

My research focuses on **natural language processing** and **machine learning**. My research interests include:

* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Education
======
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024 - Present
  * HKUST NLP Group, supervised by Prof. Junxian He
* **B.Eng.**, Shanghai Jiao Tong University, 2020 - 2024 (graduated in June 2024)
  * Advised by Prof. Junxian He

Research Experience
======
* **Research Intern**, MINIMAX, February 2025 - Present
* **Research Intern**, Tencent WXG, June 2024 - September 2024
  * Advised by Zifei Shan
* **Research Intern**, Shanghai AI Lab, June 2023 - December 2023
  * Advised by Prof. Yu Cheng

Publications
======

Conference Papers
------
{% for post in site.publications reversed %}
  {% if post.category == 'conferences' %}
**[{{ post.title }}]({{ post.url | prepend: base_path }})** ({{ post.date | date: "%Y" }})<br />
{{ post.citation }}
  {% endif %}
{% endfor %}

Preprints
------
{% for post in site.publications reversed %}
  {% if post.category == 'preprints' %}
**[{{ post.title }}]({{ post.url | prepend: base_path }})** ({{ post.date | date: "%Y" }})<br />
{{ post.citation }}
  {% endif %}
{% endfor %}

Honors and Awards
======
* **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

Skills
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Contact
======
* **Email**: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* **GitHub**: [Vicent0205](https://github.com/Vicent0205)
* **Google Scholar**: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* **X (Twitter)**: [@junteng88716710](https://twitter.com/junteng88716710)
