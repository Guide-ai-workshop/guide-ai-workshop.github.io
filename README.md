---
layout: home
title: Homepage
nav_exclude: false
permalink: /:path/
seo:
  type: Workshop
  name: Guide-AI
---

<!--<img src="/assets/images/logo.png" width="800" height="100">-->
<!--<img src="/assets/images/guide-AI-logo1.png" height="200">-->
<img src="/assets/images/workshop_logo.png" height="100">

# **Guide-AI Workshop @ SIGMOD2024**

Guide-AI seeks to **foster convergence between data management researchers and the broad Responsible AI researchers from neighboring communities like AI, Machine Learning, and Theoretical Computer Science**, to cultivate an environment for identifying challenges, exploring visionary solutions, and paving the way for the data management community to actively contribute to this pivotal research domain. 

The workshop will publish both regular research papers (8 pages plus unlimited references) describing preliminary or completed research results, as well as short papers (up to 4 pages) such as reports on applications and tools or preliminary results, interesting use cases, challenges, datasets, benchmarks, visionary ideas, and tools related to Responsible AI. Submissions should follow the guidelines as for [SIGMOD 2024](https://2024.sigmod.org/), i.e. use the sigconf template for the [ACM proceedings format](https://www.acm.org/publications/proceedings-template). 
You are welcome to view our:

- [Topics of Interest](#topics-of-interest)
- [Important Dates and Submission Guidelines](#important-dates-and-submission-guidelines)
- [Call for Papers](#call-for-papers)
<!--- - [Invited Speakers](#invited-speakers) -->
<!--- - [Schedule](#schedule) -->
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


<!---- 
## Keynote 1

[Steven Whang](https://stevenwhang.com)

### Title: Towards a Holistic Framework for Data-centric Responsible AI

### Abstract 

Responsible AI is becoming critical as AI is widely used in our everyday lives. Many companies that deploy AI publicly state that when training a model, we not only need to improve its accuracy, but also need to guarantee that the model does not discriminate against users (fairness), is resilient to noisy or poisoned data (robustness), protects personal information (privacy), and is interpretable (explainability) among others. In addition, these objectives are not only relevant to model training, but to all steps of machine learning starting from the data. A holy grail challenge is to support all of these objectives in one holistic framework that is also easy to use. To this end, I will give an overview of the data-centric responsible AI research in the Data Intelligence Lab at KAIST. I will first introduce fairness techniques throughout the machine learning process: fair model training using sample selection (ICLR’21), fair data labeling (VLDB’24, ACM SIGMOD’23), and fair data acquisition (ACM SIGMOD’21). Next, I will explain our works on other responsible AI objectives: fair and robust training (NeurIPS’21, ICML’20), privacy using disinformation (AAAI’23), and explainability-first clustering (AAAI’23). We believe we are just scratching the surface of a truly holistic solution and that many exciting challenges lie ahead.

#### Covered papers:

- Roh et al., "FairBatch: Batch Selection for Model Fairness", ICLR 2021
- Zhang et al., "iFlipper: Label Flipping for Individual Fairness", SIGMOD 2023
- Tae et al., “Falcon: Fair Active Learning using Multi-armed Bandits”, VLDB 2024
- Tae and Whang, "Slice Tuner: A Selective Data Acquisition Framework for Accurate and Fair Machine Learning Models", SIGMOD 2021
- Roh et al., "Sample Selection for Fair and Robust Training", NeurIPS 2021
- Heo and Whang, "Redactor: A Data-Centric and Individualized Defense against Inference Attacks", AAAI 2023
- Hwang and Whang, "XClusters: Explainability-first Clustering", AAAI 2023

### Bio

Steven Euijong Whang is an associate professor with tenure at KAIST EE and AI and leads the Data Intelligence Lab. His research interests include Responsible AI and Data-centric AI. He is an Associate Editor of IEEE TKDE (2023-2025), IEEE DE Bulletin (2023, 2024), and VLDB 2025. Previously he was a Research Scientist at Google Research and co-developed the data infrastructure of the TensorFlow Extended (TFX) machine learning platform. Steven received his Ph.D. in computer science in 2012 from Stanford University and his B.S. in computer science from KAIST in 2003. He was a Kwon Oh-Hyun Endowed Chair Professor (2020-2023) and received a Google AI Focused Research Award (2018, the first in Asia).


## Keynote 2

[Felix Naumann]([https://stevenwhang.com](https://hpi.de/naumann/people/felix-naumann.html))

### Title: Data Quality in the Age of AI

### Abstract 

Data quality comprises a large set of dimensions, covering many facets including simple statistics, syntactic problems, factual errors, and organizational and business aspects. With the current trend in data-oriented sciences and the increasing reliance on machine learning methods and AI systems, the challenges of poor data quality are ever more apparent. Even recent legislation, such as the EU AI Act, mentions data quality requirements for training data. With it, the notion of data quality extends to novel dimensions, such as fairness, diversity, or explainability. In the talk we shall highlight past research in this field and point out current challenges and research opportunities.



### Bio

Felix Naumann studied mathematics, economy, and computer sciences at the University of Technology in Berlin and completed his PhD thesis in the area of data quality at Humboldt University of Berlin in 2000. After a PostDoc position at the IBM Almaden Research Center working on data integration topics, he became assistant professor for information integration, again at the Humboldt-University of Berlin in 2003. Since 2006 he holds the chair for Information Systems at the Hasso Plattner Institute (HPI) at the University of Potsdam in Germany. He has been visiting researcher at QCRI, AT&T Research, IBM Research, and SAP. His research interests include data profiling, data quality and cleansing, and data integration, recorded in over 200 scientific publications. Next to numerous PC memberships for international conferences, he has organized several conferences in various roles, including VLDB 2021 as PC co-chair, and he is the Editor-in-Chief of the ACM Journal of Data and Information Quality (JDIQ).



## Panel Discussion: The Role of Data Management Research for Responsible AI

- Sudeepa Roy (Duke University)
- Boris Glavic (University of Illinois at Chicago)
- Felix Naumann (Hasso Plattner Institute, University of Potsdam)
- Steven Whang (KAIST)
- Fatemeh Nargesian (University of Rochester)

## Schedule

TBD
-->

## Important Dates and Submission Guidelines

{% for module in site.modules %}
{{ module }}
{% endfor %}

### Submission Guidelines

There are two tracks available in Guide-AI:

- Regular track (research and industrial papers; up to 8 pages, plus unlimited references)
- Short Papers (preliminary results, challenges, datasets, benchmarks, visionary solutions; up to 4 pages)

Authors will prepare their submissions according to the [ACM proceedings format](https://www.acm.org/publications/proceedings-template) consistent with the SIGMOD submission guidelines. Please use the latest ACM paper format with the sigconf template. Guide-AI has a double-blind review policy, thus **authors must not include their names and affiliations on the manuscript**.

**Submission website**: [https://cmt3.research.microsoft.com/GUIDEAI2024](https://cmt3.research.microsoft.com/GUIDEAI2024)

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
