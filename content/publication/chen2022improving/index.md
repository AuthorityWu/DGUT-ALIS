---
# title: "An example conference paper"
title: "Improving Energy-Based Out-of-Distribution Detection by Sparsity Regularization"
authors:
- Qichao Chen
- Wenjie Jiang
- Kuan Li
- Yi Wang

date: ""
doi: "10.1007/978-3-031-05936-0_42"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Advances in Knowledge Discovery and Data Mining 26th Pacific-Asia Conference*
publication_short: In *PAKDD2022*

abstract: Out-of-distribution (OOD) detection is critical for safely deploying machine learning models in the open world. Recently, an energy-score based OOD detector was proposed for any pre-trained classification models. The energy score, which is less susceptible to overconfidence, proves to be a better substitute for the conventional approaches leveraging the softmax confidence score. However, current energy-score based methods rely heavily on large-scale auxiliary datasets and introduce several dataset-dependent hyperparameters. In this paper, we propose a simple yet effective sparsity-regularized learning objective for deep neural networks so that the energy-based detector works better. Our learning objective is parameter-free and its key idea is to enlarge the differences between network outputs of in-distribution data and OOD data by regularizing the networks to generate high sparsity representations for in-distribution data. We also contribute to a tiny auxiliary outlier dataset to replace the previous one, which reduces the volume size significantly (230G vs. 40M). Besides, a new energy-score based OOD detector named Sparsity-Regularized Outlier Exposure (SROE) is proposed to incorporate the proposed sparsity-regularized loss function into the traditional Outlier Exposure method. Experimental results show that the proposed sparsity-regularized loss strategy is effective, and the SROE OOD detector outperforms the other SOTA methods with a large margin. The source code and dataset are available at https://github.com/kuan-li/SparsityRegularization.

# Summary. An optional shortened abstract.
# summary: We encouraging ensemble diversity on learning high-level feature representations and gradient dispersion in simultaneous training of deep ensemble networks.


# links:
url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-05936-0_42
url_code: https://github.com/kuan-li/SparsityRegularization
# url_code: ''
# url_dataset: ''
# url_poster:  https://virtual.2021.aaai.org/paper_AAAI-7120.html
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''
---
---
