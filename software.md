---
layout: page
title: Software
permalink: /Software/
---
While most of the papers that I have published have associated github repositories, this page is reserved for projects which I have contributed for that are intended to be used by anyone who wishes to.
### rSNAPSIM (RNA Sequence to NAscent Protein SIMulator)

<p align="center">
<img  src="/assets/rsnapsim.png" alt="rsnapsim" style="width: 500px" />
</p>

 This GUI is largely the work of Will Raymond and Luis Aguilera in Brian Munsky's group at Colorado State. It is a software package which allows one to simulate dynamics of translating proteins using amino-acid specific elongation rates. For full details, see below. I contributed C++ codes to speed up Gillespie simulations as well as some of the original Python codes for simulating stochastic elongation of nascent proteins. 

([Code](https://github.com/MunskyGroup/rSNAPsim),[Publication](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007425))


### MicroMator

<p align="center">
<img  src="/assets/micromator.png" alt="micromator" style="width: 500px" />
</p>

This provides a software framework for reactive microscopy using Python. It provides an event system API to perform imaging and real-time image analysis, such as cell segmentation/tracking, and subsequently allow the microscope to react to new circumstances, for example by performing real-time control of protein production in individual yeast. Much of the core framework of the software was developed by Steven Fletcher at Institut Pasteur. I wrote the cell segmentation and tracking pipelines, as well as the single-cell control modules. See the (manuscript)[https://www.biorxiv.org/content/10.1101/2021.03.12.435206v4.full.pdf] for further details on the neat applications that this framework enables.  

([Code](https://gitlab.inria.fr/InBio/Public/micromator))
