---
# title: "An example conference paper"
title: "G2Face: High-Fidelity Reversible Face Anonymization via Generative and Geometric Priors"
authors:
- Haoxin Yang 
- Xuemiao Xu 
- Cheng Xu 
- Huaidong Zhang
- Jing Qin
- Yi Wang
- Pheng-Ann Heng
- Shengfeng He

date: ""
doi: "10.1109/TIFS.2024.3449104"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In * IEEE Transactions on Information Forensics and Security.*
publication_short: In *TIFS2024*

abstract: Reversible face anonymization, unlike traditional face pixelization, seeks to replace sensitive identity information in facial images with synthesized alternatives, preserving privacy without sacrificing image clarity. Traditional methods, such as encoder-decoder networks, often result in significant loss of facial details due to their limited learning capacity. Additionally, relying on latent manipulation in pre-trained GANs can lead to changes in ID-irrelevant attributes, adversely affecting data utility due to GAN inversion inaccuracies. This paper introduces G 2 Face, which leverages both generative and geometric priors to enhance identity manipulation, achieving high-quality reversible face anonymization without compromising data utility. We utilize a 3D face model to extract geometric information from the input face, integrating it with a pre-trained GAN-based decoder. This synergy of generative and geometric priors allows the decoder to produce realistic anonymized faces with consistent geometry. Moreover, multi-scale facial features are extracted from the original face and combined with the decoder using our novel identity-aware feature fusion blocks (IFF). This integration enables precise blending of the generated facial patterns with the original ID-irrelevant features, resulting in accurate identity manipulation. Extensive experiments demonstrate that our method outperforms existing state-of-the-art techniques in face anonymization and recovery, while preserving high data utility.

# Summary. An optional shortened abstract.
# summary: We encouraging ensemble diversity on learning high-level feature representations and gradient dispersion in simultaneous training of deep ensemble networks.


# links:
url_pdf: https://ieeexplore.ieee.org/document/10644096
# url_code: https://github.com/ALIS-Lab/AAAI2021-PDD
# url_code: ''
# url_dataset: ''
# url_poster:  https://virtual.2021.aaai.org/paper_AAAI-7120.html
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''
---
---
