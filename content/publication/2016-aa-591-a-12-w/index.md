---
title: 'Cygrid: A fast Cython-powered convolution-based gridding module for Python'
authors:
- B. Winkel
- D. Lenz
- L. Flöer
date: '2016-06-01'
publishDate: '2024-04-15T21:48:45.352290Z'
publication_types:
- article-journal
publication: '*åp*'
doi: 10.1051/0004-6361/201628475
abstract: "Context. Data gridding is a common task in astronomy and many other science
  disciplines. It refers to the resampling of irregularly sampled data to a regular
  grid.  Aims: We present cygrid, a library module for the general purpose programming
  language Python. Cygrid can be used to resample data to any collection of target
  coordinates, although its typical application involves FITS maps or data cubes.
  The FITS world coordinate system standard is supported.  Methods: The regridding
  algorithm is based on the convolution of the original samples with a kernel of arbitrary
  shape. We introduce a lookup table scheme that allows us to parallelize the gridding
  and combine it with the HEALPix tessellation of the sphere for fast neighbor searches.\
  \  Results: We show that for n input data points, cygrids runtime scales between
  O(n) and O(nlog n) and analyze the performance gain that is achieved using multiple
  CPU cores. We also compare the gridding speed with other techniques, such as nearest-neighbor,
  and linear and cubic spline interpolation.  Conclusions: Cygrid is a very fast and
  versatile gridding library that significantly outperforms other third-party Python
  modules, such as the linear and cubic spline interpolation provided by SciPy. <A
  href=``http://github.com/bwinkel/ cygrid''>https://github.com/bwinkel/cygrid</A>"
tags:
- 'methods: numerical'
- 'techniques: image processing'
- Astrophysics - Instrumentation and Methods for Astrophysics
links:
- name: arXiv
  url: https://arxiv.org/abs/1604.06667
---
