+++
date = "2018-08-22"
title = "Geometry-Aware Metropolis Light Transport"
authors = ["Hisanari Otsu", "Johannes Hanika", "Toshiya Hachisuka", "Carsten Dachsbacher"]
url_doi = "https://doi.org/10.1145/3272127.3275106"
url_pdf = "download/geomlt.pdf"
pdf_filesize = "23.9 MB"
url_code = ""
url_pptx = ""
pptx_filesize = ""
code_is_not_available = true
code_is_coming_soon = false

abstract = "Markov chain Monte Carlo (MCMC) rendering utilizes a sequence of correlated path samples which is obtained by iteratively mutating the current state to the next. The efficiency of MCMC rendering depends on how well the mutation strategy is designed to adapt to the local structure of the state space. We present a novel MCMC rendering method that automatically adapts the step sizes of the mutations to the geometry of the rendered scene. Our geometry-aware path space perturbation largely avoids tentative samples with zero contribution due to occlusion. Our method limits the mutation step size by estimating the maximum opening angle of a cone, centered around a segment of a light transport path, where no geometry obstructs visibility. As this cone estimation introduces a considerable overhead if done naively, to make our approach efficient, we discuss and analyze fast approximate methods for cone angle estimation which utilize the acceleration structure already present for the ray-geometry intersection. Our new approach, integrated into the framework of Metropolis light transport, can achieve results with lower error and less artifact in equal time compared to current path space mutation techniques."



publication = "Hisanari Otsu, Johannes Hanika, Toshiya Hachisuka, Carsten Dachsbacher. **Geometry-Aware Metropolis Light Transport**. ACM Transactions of Graphics (Proc. of SIGGRAPH Asia). 37, 6, Article 278. 2018."
publication_short = "SIGGRAPH Asia 2018"

bibtex = """
@article{otsu2018geomlt
  title = {Geometry-Aware Metropolis Light Transport},
  author = {Hisanari Otsu and Johannes Hanika and Toshiya Hachisuka and Carsten Dachsbacher},
  journal = {ACM Transactions on Graphics (Proc. of SIGGRAPH Asia)},
  year = 2018,
  volume = 37,
  number = 6,
  pages = {278:1--278:11},
  articleno = 278,
}"""

+++
