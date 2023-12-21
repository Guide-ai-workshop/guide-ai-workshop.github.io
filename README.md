---
layout: home
title: Guide-AI
nav_exclude: true
permalink: /:path/
seo:
  type: Workshop
  name: Guide-AI
---

# Guide-AI Workshop @ SIGMOD2024

Guide-AI seeks to **foster convergence between data management researchers and the broad Responsible AI researchers from neighboring communities like AI, Machine Learning, and Theoretical Computer Science**, to cultivate an environment for identifying challenges, exploring visionary solutions, and paving the way for the data management community to actively contribute to this pivotal research domain. 
The workshop solicits regular research papers (8 pages plus unlimited references) describing preliminary or completed research results, as well as short papers (up to 4 pages) such as reports on applications and tools or preliminary results, interesting use cases, problems, datasets, benchmarks, visionary ideas, and descriptions of system components and tools related to Responsible AI. Submissions should follow the guidelines as for [SIGMOD 2024](https://2024.sigmod.org/), i.e. use the sigconf template for the [ACM proceedings format](https://www.acm.org/publications/proceedings-template). 
You are welcome to view our:

- [Topics of Interest](#topics-of-interest)
- [Important Dates](#important-dates-and-submission-guidelines)
- [Call for Papers](#call-for-papers)
- [Organizing Team](#team)

## Topics of Interest

Areas of interest for the workshop include:

1. Fairness, accountability, transparency, trustworthiness of all aspects of data management and Machine Learning.
2. Explainability of complex data manipulations.
3. Role of Data Integration and Quality Management in ML pipelines.
4. Database Repair techniques and data manipulations to handle noise and ensure fairness for removing bias.
5. Provenance for responsible data tracking, access control, and controlling data leakage.
6. Use of Causal Inference principles for responsible analytics and explanations.
7. Privacy for responsible data access.
8. Human in the loop tools for responsible AI.
9. Information visualization and UX design and its influence on bias.
10. Software audits and testing, Debugging.
11. System design and Algorithmic impacts on social phenomena.
12. Data Discovery and Governance of data sharing
13. Interdisciplinary techniques: Collaboration with domain experts

## Important Dates and Submission Guidelines

{% for module in site.modules %}
{{ module }}
{% endfor %}

### Submission Guidelines

TBD

## Call for Papers

In light of recent advancements in data-driven technologies, AI is reshaping every aspect of human life and societies.
Such a versatile impact of this double-edged sword necessitates a careful understanding and implementation of these technologies to minimize their harms, while maximizing their benefits.
The foundation of AI lies in data; hence any successful attempt would require a conscientious to data in order to effectively address the issues at the root.
Conversely, most of the attempts have been on achieving responsible AI, given a dataset at hand, overlooking the role of its construction and assumptions.
This workshop is an attempt to fill this gap by giving a special attention to GUIDE AI, to govern, understand, and integrate data for effective and responsible AI.
This workshop specifically seeks to foster convergence between data management researchers and the broad Responsible AI researchers from neighboring communities like AI, Machine Learning, and Theoretical Computer Science, to cultivate an environment for identifying challenges, exploring visionary solutions, and paving the way for the data management community to actively contribute to this pivotal research domain. The workshop will provide a forum for:

- *Community Convergence*: Data management researchers have the expertise to address data related problems. They have been focused to solve technical and challenging data problems. As a result, elegant solutions are constantly proposed to develop efficient, effective, and scalable data systems. Responsibility, however, has not been a main research objective for meany of the researchers in this community. On the other hand, the responsible AI community may not have the proper expertise or interest to approach the problem at the data level. As a result, most of their focus have been on achieving responsibility at the model construction level. A main objective of this workshop is to converge these two communities together by inviting outstanding researchers both inside and outside the data management community to give keynote talks and to present their findings. This will enable to potential to initiate interesting cross-community discussions.
- *Identifying Challenges*: Facilitating exposure of data management researchers to responsible AI issues serves as a catalyst for identifying intricate data challenges, resulting in the discovery of innovative research within the data management community.
- *Exploring Visionary Solutions*: Beyond pinpointing the challenges, this workshop aims at identifying both visionary and in-depth solution by the data management researchers. We particularly hope to encourage the community to embrace responsibility as a first-class citizen in their research.

## Team

### Chairs

{% assign instructors = site.staffers | where: 'role', 'Co-Chair' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'PC' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Program Committee

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
