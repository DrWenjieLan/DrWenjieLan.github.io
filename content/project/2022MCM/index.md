---
title: A Synthetical Water Dispatching Model Give it or Give up
date: 2022-01-26
external_link: https://drive.google.com/file/d/1AjyUT71oaK3dRCkGMek5OINJll7FmgyN/view?usp=sharing
tags:
  - Muti-interest Tradeoff
  - Dynamic Programming
---
**Competition**: Mathematical Contest in Modelling
**Award**: Finalist (Top: 2\% among 27,205 Teams)
**Awarded by**: the Consortium for Mathematics and Its Applications
# Water Loss in Dams Due to Climate Change: A Mathematical Approach

Water loss in dams resulting from climate change has become a prominent problem in recent years, thus influencing humans’ life and production. To help address this issue, mathematical models are required to be established.

## **Problem 1**

Problem 1 can be divided into three parts:

1. **Service Area Coordination**:
   - Maps are rasterized, and service areas for two dams are classified using a **Comparative Optimization Algorithm**.

2. **Comprehensive Dispatching Model for Water**:
   - **Demand Side**: An **AIR Model** is established to capture water demands, resulting in:
     - **11858569 m³** to be drawn from the Glen Canyon Dam.
     - **40978282 m³** to be drawn from the Hoover Dam.
   - **Supply Side**: Analysis of water levels and water volumes is conducted, with water-electricity generation fitted through **Polynomial Interpolation**, laying the foundation for subsequent analysis.

3. **Dynamic Programming Model**:
   - Calculates the time until demands are unmet at fixed water levels:
     - For the highest water level, the time is **495 days**.
   - Additional water as a function of time is derived (see Section 4.6).
   - To consider Mexico’s residual claims, a **Water-Supply Corridor Model** is proposed, balancing respect for rights and interests (see Section 4.7).

## **Problem 2**

A **Multi-Interest Tradeoff Model** is developed using **Goal Programming** and **Input-Output Theory**:

1. **Economic Benefits as Criteria**:
   - Four "players" of competing interests are identified.
   - Results include:
     - **11848077 m³** drawn from the Glen Canyon Dam.
     - **39125274 m³** drawn from the Hoover Dam.
   - Reallocation results in increased water for industry and decreased water for agriculture (see Section 5.2, Table 5).

## **Problem 3**

When supply cannot meet all water demand:

- Inspired by the **NSGA-II Algorithm** (a type of Genetic Algorithm), specific approaches are recommended:
  1. **Reducing the scale of industries** with low water-use efficiency and allocating more water to efficient industries.
  2. **Promoting technological innovation** in industries with low water-use efficiency to improve resource utilization.

## **Conclusion**

To ensure robustness, sensitivity analysis is conducted, and a summary article containing findings and suggestions has been written for the *Drought and Thirst Magazine*.




<!--more-->
