---
layout: home
title: Keynotes
nav_exclude: false
permalink: /:path/keynotes
seo:
  type: Workshop
  name: Guide-AI
---

<img src="/assets/images/workshop_logo.png" height="100">

# Invited Speakers

## Keynote 1

{% assign instructors = site.staffers | where: 'role', 'Steven' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

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

{% assign instructors = site.staffers | where: 'role', 'Felix' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

### Title: Data Quality in the Age of AI

### Abstract 

Data quality comprises a large set of dimensions, covering many facets including simple statistics, syntactic problems, factual errors, and organizational and business aspects. With the current trend in data-oriented sciences and the increasing reliance on machine learning methods and AI systems, the challenges of poor data quality are ever more apparent. Even recent legislation, such as the EU AI Act, mentions data quality requirements for training data. With it, the notion of data quality extends to novel dimensions, such as fairness, diversity, or explainability. In the talk we shall highlight past research in this field and point out current challenges and research opportunities.



### Bio

Felix Naumann studied mathematics, economy, and computer sciences at the University of Technology in Berlin and completed his PhD thesis in the area of data quality at Humboldt University of Berlin in 2000. After a PostDoc position at the IBM Almaden Research Center working on data integration topics, he became assistant professor for information integration, again at the Humboldt-University of Berlin in 2003. Since 2006 he holds the chair for Information Systems at the Hasso Plattner Institute (HPI) at the University of Potsdam in Germany. He has been visiting researcher at QCRI, AT&T Research, IBM Research, and SAP. His research interests include data profiling, data quality and cleansing, and data integration, recorded in over 200 scientific publications. Next to numerous PC memberships for international conferences, he has organized several conferences in various roles, including VLDB 2021 as PC co-chair, and he is the Editor-in-Chief of the ACM Journal of Data and Information Quality (JDIQ).
