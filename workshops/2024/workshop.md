---
layout: page
navtitle: Workshops
title: 3rd BEAST Workshop, 2024
description: "Third annual BEAST workshop"
permalink: /workshops/2024/
---

# 3rd BEAST Workshop, 2024

<b>August 22 - 23, 2024, 9 am - 5 pm MDT</b> in hybrid in-person/online mode at:

+ JSCBB (CU Boulder), 3415 Colorado Ave, Boulder CO, USA, and
+ Online (on Zoom)

## Agenda

Please review [Setup instructions](setup) before / at the start of the workshop.

### Day 1: Thursday, August 22, 2024

+ **9:00 am MDT** [Welcome, introduction to BEAST](beast.pdf)
+ **9:10 am MDT** [Introduction to Joint Density-Functional Theory (JDFT)](jdft.pdf)
+ **9:45 am MDT** [JDFT calculations in practice with JDFTx (and a QimPy intro)](jdftx.pdf)
+ **10:00 am MDT** Practical DFT session I: molecules and solids
+ **12:00 pm MDT** Break for lunch
+ **1:00 pm MDT**  Practical DFT session II: surfaces and adsorbates
+ **3:00 pm MDT**
   - **Option 1**:  Practical DFT session III: electrocatalytic pathways
   - **Option 2**:  Practical DFT calculations with QimPy
+ **5:00 pm MDT** Adjourn

### Day 2: Friday, August 23, 2024

+ **9:00 am MDT** [Introduction to JDFT+RPA: Theory and applications](rpa.pdf)
+ **9:30 am MDT** [JDFT+RPA calculations in practice with JDFTx+BGW](jdftx-bgw.pdf)
+ **9:50 am MDT** Introduction to machine-learned interatomic potentials
+ **10:00 am MDT**
   - **Option 1**: Practical JDFTx+BGW session for RPA adsorption energies
   - **Option 2**: Continue Practical DFT sessions II and III
+ **12:00 pm MDT** Break for lunch
+ **1:00 pm MDT** [BEAST DB: preview and opportunity for community contributions](beastdb.pdf)
+ **2:00 pm MDT** 
   - **Option 1**: Machine-learned interatomic potentials for adsorption energies
   - **Option 2**: Continue JDFTx+BGW session for RPA adsorption energies
+ **4:00 pm MDT** Panel discussions, Q&amp;A, feature requests
+ **5:00 pm MDT** Adjourn 

## Original announcement

[Register here](https://forms.gle/ydLz6Fu7Qpfb7ysW9) (free).
The workshop starts on the last day of the ACS Fall Meeting at Denver, CO, making it convenient for ACS attendees to join us in person nearby in Boulder, CO.

We are excited to announce the 3rd Annual BEAST (Beyond-DFT Electrochemistry with Accelerated and Solvated Techniques) Workshop.
This BEAST workshop will include hands-on user sessions on simulation methods best suited for studying electrocatalysis.
The methods will include grand-canonical DFT (GC-DFT) with the latest solvation methods implemented in the JDFTx and/or QimPy computational packages, beyond-DFT random phase approximation (RPA) calculations in the BerkeleyGW package, and our recently released GC-DFT electrocatalysis database, [BEAST DB](https://beastdb.nrel.gov).
The target participants for the Workshop are graduate students, postdocs, and researchers who are interested in learning about or sharpening their skills on ab initio calculations of electrocatalytic systems, including the effect of solvation, self-consistent applied potential and beyond-DFT exchange-correlation effects.

This third workshop will once again start from basics, but provide options for more advanced calculations, building on previous year's workshops. 
It will introduce the basic theory of solvation, GC-DFT and RPA, standard and new features of the JDFTx and BerkeleyGW packages, with detailed examples of using the JDFTx and BerkeleyGW packages.
Finally, we will also introduce development in the new QimPy code and solicit community involvement in its continued development.

The [JDFTx package](https://jdftx.org) is a plane-wave density functional theory (DFT) code that calculates the electronic properties of optoelectronic and electrocatalytic systems, with a particular strength in describing solvated system under applied bias. JDFTx supports a range of exchange correlation functionals, dispersion corrections, several formats of norm-conserving and ultrasoft pseudopotentials that are pre-installed, and calculations of systems of any dimensionality from 0 to 3: molecules, wires, slabs / 2D materials and bulk.
The [QimPy package](https://qimpy.org) is the next iteration of JDFTx, rewritten from scratch in Python with PyTorch to more easily take advantage of a diverse set of accelerators and to further ease development. 
This workshop will cover exercises in both JDFTx and QimPy, leveraging JDFTx for mature features and introducing QimPy for its greater scalability and future ease of use.
The [BerkeleyGW Package](https://berkeleygw.org) calculates the electronic structure and total energies of electrocatalytic systems at the RPA level in this context.
