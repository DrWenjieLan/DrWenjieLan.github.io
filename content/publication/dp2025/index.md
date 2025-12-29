---
title: "Differentially Private Computation of the Gini Index for Income InequalityU"
authors:
- admin
- “Jerome Reiter”
date: "2025-11-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Journal Paper"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: | 
  The Gini index is a widely reported measure of income inequality. In some settings, the underlying data used to compute the Gini index are confidential. The organization charged with reporting the Gini index may be concerned that its release could leak information about the underlying data. We present an approach for bounding this information leakage by releasing a differentially private version of the Gini index. In doing so, we analyze how adding, deleting, or altering a single observation in any specific dataset can affect the computation of the Gini index; this is known as the local sensitivity. We then derive a smooth upper bound on the local sensitivity. Using this bound, we define a mechanism that adds noise to the Gini index, thereby satisfying differential privacy. Using simulated and genuine income data, we show that the mechanism can reduce the errors from noise injection substantially relative to differentially private algorithms that rely on the global sensitivity, that is, the maximum of the local sensitivities over all possible datasets. We characterize settings where using smooth sensitivity can provide highly accurate estimates, as well as settings where the noise variance is simply too large to provide reliably useful results. We also present a Bayesian post-processing step that provides interval estimates about the value of the Gini index computed with the confidential data.

# summary: The research aims to predict the likelihood of enterprises being classified as "Special Treatment" (ST) in the upcoming quarter using machine learning (ML) and deep learning (DL) techniques. The focus is on enhancing financial distress prediction by incorporating novel indicators beyond traditional metrics.



tags:
- Differential Privacy 

featured: true

links:
url_pdf: https://arxiv.org/abs/2511.19771
url_code: https://github.com/YancyLan/DP_Gini

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Differential Privacy'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---