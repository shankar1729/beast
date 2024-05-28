---
layout: post
title:  "∆-learning of band structures published in <i>Chem. Mater.</i>"
description: "∆-Learning enables accurate prediction of hybrid-functional band structures at semi-local cost."
date:   2023-10-16 08:30:00 -0500
---

<p style="text-align: center;">
<img alt="Bulk delta ML" src="/images/news/BulkDeltaML.jpg"/>
</p>

S Adhikari, J Clary, R Sundararaman, C Musgrave, D Vigil-Fowler, C Sutton,
&ldquo;Accurate Prediction of HSE06 Band Structures for a Diverse Set of Materials Using ∆-Learning&rdquo;,
<a href="https://doi.org/10.1021/acs.chemmater.3c01131"><i>Chem. Mater.</i> <b>35</b>, 8397–8405 (2023)</a>

We used machine learning (ML) to accurately predict eigenvalues of the hybrid HSE06 functional using eigenvalues computed by the less computationally expensive PBE functional and associated electronic features based on the k-point resolved atomic band character. The ML model was trained by using eigenvalues from only one k-point for each of the 168 compounds in the training set. The HSE06 eigenvalues across all k-points were then predicted for a separate set of 169 compounds with a mean absolute error (MAE) of 0.13 eV, representing a significant improvement over the error of PBE-computed eigenvalues relative to that of HSE06 (MAE = 0.96 eV). These accurately predicted eigenvalues result in remarkably accurate predictions for the band structures, projected density of states, and band gaps, even though the model was not explicitly trained on these other properties. Finally, we demonstrate that our ML model has a similar accuracy for both ternary and quaternary compounds well outside the initial training set and on systems with 112 and 160 atoms, demonstrating its potential to rapidly predict HSE06-quality electronic structures of complex materials that are practically unfeasible for HSE06.
