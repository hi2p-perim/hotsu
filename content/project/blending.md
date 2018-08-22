+++
date = "2017-07-14"
title = "Supervised Learning of How to Blend Light Transport Simulations"
authors = ["hisanari_otsu", "shinichi_kinuwaki", "toshiya_hachisuka"]
url_doi = "http://doi.org/10.1007/978-3-319-91436-7_23"
url_pdf = "/download/blending.pdf"
pdf_filesize = "18.3 MB"
url_code = ""
url_pptx = ""
pptx_filesize = ""
code_is_not_available = true
code_is_coming_soon = false

abstract = "Light transport simulation is a popular approach for rendering photorealistic images. However, since different algorithms have different efficiencies depending on input scene configurations, a user would try to find the most efficient algorithm based on trials and errors. This selection of an algorithm can be cumbersome because a user needs to know technical details of each algorithm. We propose a framework which blends the results of two different rendering algorithms, such that a blending weight per pixel becomes automatically larger for a more efficient algorithm. Our framework utilizes a popular machine learning technique, regression forests, for analyzing statistics of outputs of rendering algorithms and then generating an appropriate blending weight for each pixel. The key idea is to determine blending weights based on classification of path types. This idea is inspired by the same common practice in movie industries; an artist composites multiple rendered images where each image contains only a part of light transport paths (e.g., caustics) rendered by a specific algorithm. Since our framework treats each algorithm as a black-box, we can easily combine very different rendering algorithms as long as they eventually generate the same results based on light transport simulation. The blended results with our algorithm are almost always more accurate than taking the average, and no worse than the results with an inefficient algorithm alone."

publication = "Hisanari Otsu, Shinichi Kinuwaki and Toshiya Hachisuka. **Supervised Learning of How to Blend Light Transport Simulations**. Monte Carlo and Quasi-Monte Carlo Methods (MCQMC 2016). 2018."
publication_short = "Proceedings of the MCQMC 2016"

bibtex = """
@inproceedings{otsu2018blending,
  author="Hisanari Otsu and Shinichi Kinuwaki and Toshiya Hachisuka",
  title="Supervised Learning of How to Blend Light Transport Simulations",
  booktitle="Monte Carlo and Quasi-Monte Carlo Methods (MCQMC 2016)",
  year="2018",
  pages="409--427",
}
"""

+++
