---
title: "Fast Ewald summation for free-space Stokes potentials"
date: 2017-12-01
publishDate: 2019-05-31T19:23:26.878984Z
authors: ["Ludvig af Klinteberg", "Davoud Saffar Shamshirgar", "Anna-Karin Tornberg"]
publication_types: ["2"]
abstract: "We present a spectrally accurate method for the rapid evaluation of free-space Stokes potentials, i.e. sums involving a large number of free space Green's functions. We consider sums involving stokeslets, stresslets and rotlets that appear in boundary integral methods and potential methods for solving Stokes equations. The method combines the framework of the Spectral Ewald method for periodic problems, with a very recent approach to solving the free-space harmonic and biharmonic equations using fast Fourier transforms (FFTs) on a uniform grid. Convolution with a truncated Gaussian function is used to place point sources on a grid. With precomputation of a scalar grid quantity that does not depend on these sources, the amount of oversampling of the grids with Gaussians can be kept at a factor of two, the minimum for aperiodic convolutions by FFTs. The resulting algorithm has a computational complexity of O(N log N) for problems with N sources and targets. Comparison is made with a fast multipole method (FMM) to show that the performance of the new method is competitive."
featured: false
publication: "*Res. Math. Sci.*"
doi: "10.1186/s40687-016-0092-7"
links:
 - icon_pack: ai
   icon: open-access
   name: "PDF"
   url: "http://resmathsci.springeropen.com/articles/10.1186/s40687-016-0092-7"   
---

