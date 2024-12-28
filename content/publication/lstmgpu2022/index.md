---
title: "An example preprint / working paper"
authors:
- admin
date: "2022-08-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["research"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: |
  This study focuses on predicting the probability of enterprises being categorized as "Special Treatment" (ST) in the next quarter based on historical data. The research aims to enhance financial distress prediction using machine learning and deep learning models. It explores the selection of predictive indicators beyond traditional metrics, incorporating novel features like graphical representations of stock relationships.
  Key steps includes:Data Preparation: Utilizing financial indicators from CSMAR and stock data from BaoStock, with techniques like ADASYN to handle data imbalance. Model Design: Implementing LSTM and GAT models, leveraging panel data and adjacency matrices constructed from stock industry classifications and cosine similarity measures.Results: Comparing models with and without time-series considerations, highlighting the superior performance of time-series models in prediction accuracy and AUC scores.
  The study demonstrates that advanced deep learning techniques, particularly multi-layer GAT models, effectively capture complex stock relationships and improve predictive performance, offering valuable insights for financial risk management and early warning systems. Future work will explore unstructured data like sentiment analysis and relational features based on corporate connections.





tags:
- Deep learning LSTM+GRU; Risk Management

featured: true

links:
url_pdf: https://github.com/YancyLan/LSTM_GRU_ST_Stock_Predict/blob/main/LSTM_GRU.pdf
url_code: 'https://github.com/YancyLan/LSTM_GRU_ST_Stock_Predict'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Stock Knowledge Graph'
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

