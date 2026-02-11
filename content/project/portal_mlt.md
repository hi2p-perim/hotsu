+++
date = "2018-08-22"
title = "Portal-Based Path Perturbation for Metropolis Light Transport"
authors = ["Hisanari Otsu", "Johannes Hanika", "Carsten Dachsbacher"]
url_doi = ""
url_pdf = "download/portal_mlt.pdf"
pdf_filesize = "58.8 MB"
url_code = "https://github.com/hi2p-perim/lm3_portal_mlt"
url_pptx = ""
pptx_filesize = ""
code_is_not_available = false
code_is_coming_soon = false

abstract = "Light transport simulation in scenes with difficult visibility still remains a challenging problem. Markov chain Monte Carlo (MCMC) rendering is often employed for such configurations. It generates a sequence of correlated light transport paths by iteratively mutating the current state, a path, to another. Since the proposed path is correlated to the current path, MCMC can explore regions of the path space, also with difficult visibility, once they have been found. To improve the efficiency of the exploration, we propose a path mutation strategy making use of the concept of portals. Portals are user-defined objects in the scene to guide the sampling of the difficult visibility, which have been employed in the context of non-MCMC rendering. Our mutation strategy perturbs a path edge around the intersection point of the edge and the portal, instead of perturbing the edge by moving a path vertex as in the ordinary path mutation strategies. This reduces the probability for the proposed path being rejected due to changes in visibility."


publication = "Hisanari Otsu, Johannes Hanika, Carsten Dachsbacher. **Portal-Based Path Perturbation for Metropolis Light Transport**. Proceedings of Vision, Modeling and Visualization. 2020."
publication_short = "Vision, Modeling, and Visualization 2020"

bibtex = """
@inproceedings{otsu2020portalmlt
  title = {Portal-Based Path Perturbation for Metropolis Light Transport},
  author = {Hisanari Otsu and Johannes Hanika and Carsten Dachsbacher},
  booktitle = {Proceedings of Vision, Modeling and Visualization},
  year = 2020,
}"""

+++
