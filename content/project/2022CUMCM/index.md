---
title: 2022CUMCM-B-Mathematics-Modelling
date: 2022-10-26
tags:
  - UAV Formation
  - Information Source Traceback Algorithm
  - 0-1 Optimization Model
  - Greedy Algorithm
url_pdf: https://drive.google.com/file/d/1q5-iB5_Q0yjnoDLeUWaJ7PNOU2HZz7UA/view?usp=sharing
---
**Competition:** 2022CUMCM-B-Mathematics-Modelling
**Award:** National Second Place
**Awared by:**China Society for Industrial and Applied Mathematics
This paper addresses the problem of passive localization and formation adjustment in UAV (Unmanned Aerial Vehicle) formation flying by developing models and innovative algorithms. The main contributions are summarized below:

1. **Problem 1, Subquestion 1**:
   - The task is transformed into finding the intersection points of multiple arc trajectories.
   - A universal multi-point trajectory localization model is established in polar coordinates.
   - An **Information Source Traceback Algorithm** (Appendix 2) is innovatively developed to match signal sources with UAV identifiers by comparing ideal and actual angles within an error margin. This allows solving corresponding trajectory equations and forming the final multi-point trajectory localization model (5.1.2) for UAV positioning.

2. **Problem 1, Subquestion 2**:
   - The problem is reformulated as an optimal incremental signal source planning task.
   - A 0-1 optimization model (5.2.1) is created and solved using a looped search structure.
   - The **Information Source Traceback Algorithm** is improved (Appendix 3) to account for slight UAV positional deviations. It identifies unknown UAVs by approximating their azimuthal angles. The solution reveals that adding only one UAV signal emitter achieves effective localization, excluding FY00 and FY01 (5.2.3).

3. **Problem 1, Subquestion 3**:
   - A greedy approach is used to construct an iterative optimization model for UAV positioning (5.3.1).
   - Using fixed, unbiased signal sources (FY00 and FY01) as the coordinate system, other UAVs are iteratively selected for positioning and adjustment, reducing errors through convergence in three iterations (5.3.2). This results in an effective formation adjustment scheme.

4. **Problem 2**:
   - Based on the traceback algorithm and localization model, a **conical formation adjustment scheme** is developed (5.4.1). Localization starts with three UAVs forming a central equilateral triangle and expands outward layer by layer.
   - The approach is generalized to any arbitrary formation (5.4.2), involving iterative adjustments using accurate UAV positions as references.
   - Practical application is demonstrated with an example of adjusting UAVs in a “China”-shaped formation (5.4.3).

5. **Robustness Testing**:
   - The robustness of the improved traceback algorithm is verified through angle error discussions, ensuring reliability under slight positional deviations.

## **Conclusion**
The paper emphasizes the **Information Source Traceback Algorithm** and **Multi-Point Trajectory Localization Model** as core methodologies. These are applied to real-world UAV localization and formation adjustment problems, offering optimized adjustment schemes and effective generalization to various scenarios.


<!--more-->
