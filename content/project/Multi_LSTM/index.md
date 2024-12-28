---
title: A Project on the prediction of systematic risk in stock market based on multibranch LSTM model with multidimensional heterogeneous perspective
date: 2023-12-01
external_link: https://github.com/YancyLan/LSTM-multibranch
tags:
  - Multibranch_LSTM
  - NLP
  - Risk Management
---

This project adopts multi-dimensional, heterogeneous data—covering contagion effects, textual information, and fundamentals—to construct a feature set. Contagion indicators are derived from global market indices, capturing inter-market risk structures and CoES-based correlation vectors. Text features come from A-share financial news, while fundamental indicators encompass macroeconomic, stock market, and foreign exchange data, plus historical systemic risk.

A multi-branch LSTM model is then proposed to predict systemic risk in the A-share market. Three independent LSTM branches extract information from each modality, and a separate convolutional-LSTM branch learns holistic knowledge. Results show that contagion-network features significantly enhance model performance, and the multi-branch LSTM effectively supports the monitoring and early warning of systemic risk in the stock market.

<!--more-->
