---
# title: "An example conference paper"
title: "Federated Learning with Hybrid Knowledge Distillations on Long-Tailed Heterogeneous Client Data"
authors:
- Senbin Liu
- Yuanting Zhang
- Kunhua Zhang
- Yi Wang*

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2023-09-30T00:00:00Z"
publishDate: "2024-08-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 27th European Conference on Artificial Intelligence*
publication_short: In *ECAI2024*

abstract: Federated learning (FL) has a great potential in large-scale machine learning applications by training a global model over distributed client data. However, FL deployed in real-world applications often incur collaboration bias and unstable convergence with inconsistent local predictions, resulting in poor modelling performance on heterogeneous and long-tailed client data distributions. In this paper, we reconsider heterogeneous FL in a two-stage learning paradigm where representation learning and classifier re-training are separated to incorporate different sampling schemes. This allows us to deal with the dilemma of obtaining more generalizable features and fine tuning a biased classifier building on client model aggregations. Specifically, we propose a novel hybrid knowledge distillation scheme, called FedHyb, to facilitate the two-stage learning. From the view of knowledge transfer, we show that FedHyb enables several desirable properties in the global feature space and optimization with fine-tuning, thus achieving better test accuracy and convergence speed, especially with a higher level of data heterogeneity and an increasing number of distributed clients. FedHyb does not require any information exchange between clients preventing privacy leakage, and is more robust under poisoning attacks comparing with other FL methods designed on heterogeneous data.


# Summary. An optional shortened abstract.
# summary: We encouraging ensemble diversity on learning high-level feature representations and gradient dispersion in simultaneous training of deep ensemble networks.


# links:
url_pdf: https://www.ecai2024.eu/programme/accepted-papers
# url_code: ''
# url_dataset: ''
# url_poster:  https://virtual.2021.aaai.org/paper_AAAI-7120.html
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''
---
---
