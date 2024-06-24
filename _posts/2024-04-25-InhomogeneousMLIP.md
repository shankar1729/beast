---
layout: post
title:  "ML force fields for inhomogeneous fluids published in <i>J. Comput. Chem.</i>"
description: "Imhomogeneous training data improves the reliability of machine learned interatomic potentials."
date:   2024-04-25 08:30:00 -0500
---

<p style="text-align: center;">
<img alt="Inhomogeneous MLIP" src="/images/news/InhomogeneousMLIP.jpg"/>
</p>

K. Fazel, N. Karimitari, T. Shah, C. Sutton and R. Sundararaman,
&ldquo;Improving the reliability of machine learned potentials for modeling inhomogeneous liquids&rdquo;,
<a href="https://doi.org/10.1002/jcc.27353"><i>J. Comput. Chem.</i> <b>45</b>, 1821 (2024)</a>

The atomic-scale response of inhomogeneous fluids at interfaces and surrounding solute particles plays a critical role in governing chemical, electrochemical, and biological processes. Classical molecular dynamics simulations have been applied extensively to simulate the response of fluids to inhomogeneities directly, but are limited by the accuracy of the underlying interatomic potentials. Here, we use neural network potentials (NNPs) trained to ab initio simulations to accurately predict the inhomogeneous responses of two distinct fluids: liquid water and molten NaCl. Although NNPs can be readily trained to model complex bulk systems across a range of state points, we show that to appropriately model a fluid's response at an interface, relevant inhomogeneous configurations must be included in the training data. In order to sufficiently sample appropriate configurations of such inhomogeneous fluids, we develop protocols based on molecular dynamics simulations in the presence of external potentials. We demonstrate that NNPs trained on inhomogeneous fluid configurations can more accurately predict several key properties of fluids—including the density response, surface tension and size-dependent cavitation free energies—for liquid water and molten NaCl, compared to both empirical interatomic potentials and NNPs that are not trained on such inhomogeneous configurations. This work therefore provides a first demonstration and framework to extract the response of inhomogeneous fluids from first principles for classical density-functional treatment of fluids free from empirical potentials.
