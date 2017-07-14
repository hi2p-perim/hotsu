+++
date = "2017-06-01"
title = "Fusing State Spaces for Markov Chain Monte Carlo Rendering"
authors = ["hisanari_otsu", "anton_kaplanyan", "johannes_hanika", "carsten_dachsbacher", "toshiya_hachisuka"]
url_doi = "https://doi.org/0.1145/3072959.3073691"
url_pdf = "/download/inverse.pdf"
pdf_filesize = "29.2 MB"
url_code = "#"
code_is_coming_soon = true

abstract = "Rendering algorithms using Markov chain Monte Carlo (MCMC) currently build upon two different state spaces. One of them is the path space, where the algorithms operate on the vertices of actual transport paths. The other state space is the primary sample space, where the algorithms operate on sequences of numbers used for generating transport paths. While the two state spaces are related by the sampling procedure of transport paths, all existing MCMC rendering algorithms are designed to work within only one of the state spaces. We propose a first framework which provides a comprehensive connection between the path space and the primary sample space. Using this framework, we can use mutation strategies designed for one space with mutation strategies in the respective other space. As a practical example, we take a combination of manifold exploration and multiplexed Metropolis light transport using our framework. Our results show that the simultaneous use of the two state spaces improves the robustness of MCMC rendering. By combining efficient local exploration in the path space with global jumps in primary sample space, our method achieves more uniform convergence as compared to using only one space."

publication = "Hisanari Otsu, Anton S. Kaplanyan, Johannes Hanika, Carsten Dachsbacher, and Toshiya Hachisuka. **Fusing State Spaces for Markov Chain Monte Carlo Rendering**. *ACM Transactions of Graphics (Proc. of SIGGRAPH)*. 36, 4, Article 74. 2017."
publication_short = "SIGGRAPH 2017"

bibtex = """
@article{otsu2017inverse,
  title = {Fusing State Spaces for {Markov} Chain {Monte Carlo} Rendering},
  author = {Hisanari Otsu and Anton S. Kaplanyan and Johannes Hanika and Carsten Dachsbacher and Toshiya Hachisuka},
  journal = {ACM Transactions on Graphics (Proc. of SIGGRAPH)},
  year = 2017,
  volume = 36,
  number = 4,
  pages = {74:1--74:10},
  articleno = 74,
}"""

+++
