---
title: "A parallel non-uniform fast Fourier transform library based on an \"exponential of semicircle\" kernel"
date: 2018-08-01
publishDate: 2019-05-31T19:23:26.881661Z
authors: ["Alex H. Barnett", "Jeremy F. Magland", "Ludvig af Klinteberg"]
publication_types: ["3"]
abstract: "The nonuniform fast Fourier transform (NUFFT) generalizes the FFT to off-grid data. Its many applications include image reconstruction, data analysis, and the numerical solution of differential equations. We present FINUFFT, an efficient parallel library for type 1 (nonuiform to uniform), type 2 (uniform to nonuniform), or type 3 (nonuniform to nonuniform) transforms, in dimensions 1, 2, or 3. It uses minimal RAM, requires no precomputation or plan steps, and has a simple interface to several languages. We perform the expensive spreading/interpolation between nonuniform points and the fine grid via a simple new kernel---the `exponential of semicircle' $e^{β \\sqrt{1-x^2}}$ in $x \\in [-1,1]$---in a cache-aware load-balanced multithreaded implementation. The deconvolution step requires the Fourier transform of the kernel, for which we propose efficient numerical quadrature. For types 1 and 2, rigorous error bounds asymptotic in the kernel width approach the fastest known exponential rate, namely that of the Kaiser--Bessel kernel. We benchmark against several popular CPU-based libraries, showing favorable speed and memory footprint, especially in three dimensions when high accuracy and/or clustered point distributions are desired."
featured: false
publication: "*arXiv:1808.06736 [math.NA]*"
url_preprint: "http://arxiv.org/abs/1808.06736"
url_code: https://github.com/flatironinstitute/finufft
---

