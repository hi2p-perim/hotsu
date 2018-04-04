+++
date = "2018-04-04"
title = "Reproducing Spectral Reflectances from Tristimulus Colors"
authors = ["hisanari_otsu", "masafumi_yamamoto", "toshiya_hachisuka"]
url_doi = "https://doi.org/10.1111/cgf.13332"
url_pdf = "/download/rgb2spec.pdf"
pdf_filesize = "29.9 MB"
url_code = ""
url_pptx = ""
pptx_filesize = ""
code_is_coming_soon = true

abstract = "Physically based rendering systems often support spectral rendering to simulate light transport in the real world. Material representations in such simulations need to be defined as spectral distributions. Since commonly available material data are in tristimulus colours, we ideally would like to obtain spectral distributions from tristimulus colours as an input to spectral rendering systems. Reproduction of spectral distributions given tristimulus colours, however, has been considered an ill‐posed problem since single tristimulus colour corresponds to a set of different spectra due to metamerism. We show how to resolve this problem using a data‐driven approach based on measured spectra and propose a practical algorithm that can faithfully reproduce a corresponding spectrum only from the given tristimulus colour. The key observation in colour science is that a natural measured spectrum is usually well approximated by a weighted sum of a few basis functions. We show how to reformulate conversion of tristimulus colours to spectra via principal component analysis. To improve accuracy of conversion, we propose a greedy clustering algorithm which minimizes reconstruction error. Using pre‐computation, the runtime computation is just a single matrix multiplication with an input tristimulus colour. Numerical experiments show that our method well reproduces the reference measured spectra using only the tristimulus colours as input."

publication = "Hisanari Otsu, Masafumi Yamamoto, and Toshiya Hachisuka. **Reproducing Spectral Reflectances From Tristimulus Colours**. *Computer Graphics Forum (to appear)*. 2018."
publication_short = "Computer Graphics Forum"

bibtex = ""

+++
