---
layout: archive
title: "Softwares"
permalink: /softwares/
author_profile: true
others: ""
---
## CMDM: Color Mesh Distortion Measure
------
<p style='text-align: justify;'> CMDM is the first metric for quality assessment of 3Dmeshes with diffuse colors, which works entirely on the mesh domain, at vertex level. It is a full-reference data-driven multiscale metric, that incorporates perceptually-relevant curvature-based and color-based features. 

Our framework is as follows: For given distorted M<sub>dist</sub> and reference M<sub>ref</sub> meshes, we first establish a correspondence between M<sub>dist</sub> and M<sub>ref</sub>. 
Then for each scale h<sub>i</sub>, we define a spherical neighborhood around each vertex v of M<sub>dist</sub> and compute a set of local geometry and color based features over the points belonging to the neighborhood of v and their corresponding points on  M<sub>ref</sub>. 
Local single-scale feature values are pooled into global multiscale features. Finally, CMDM is defined as a linear combination of an optimal subset of features determined through logistic regression.</p>
> CMDM code is available in the [MEPP2 platforms](https://github.com/MEPP-team/MEPP2).
|	[Manual](http://yananehme.github.io/files/Manual_CMDM.pdf)	|	[Project page](https://projet.liris.cnrs.fr/pisco/)	|	[bibtex](http://yananehme.github.io/files/bbb.bib)	|
<img style="float: right;" src='/images/Mepp2_logo.jpg'>

