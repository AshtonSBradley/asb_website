---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Numerical Method for the Stochastic Projected Gross-Pitaevskii Equation
subtitle: ''
summary: ''
authors:
- S J Rooney
- P Blair Blakie
- A S Bradley
tags: []
categories: []
date: '2014-01-01'
lastmod: 2022-01-25T13:21:28+13:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [cfields]
publishDate: '2022-01-25T00:21:28.341894Z'
publication_types:
- '2'
abstract: We present a method for solving the stochastic projected Gross-Pitaevskii
  equation (SPGPE) for a three- dimensional weakly interacting Bose gas in a harmonic-oscillator
  trapping potential. The SPGPE contains the challenge of both accurately evolving
  all modes in the low-energy classical region of the system, and evaluating terms
  from the number-conserving scattering reservoir process. We give an accurate and
  efficient procedure for evaluating the scattering terms using a Hermite-polynomial
  based spectral-Galerkin representation, which allows us to precisely implement the
  low-energy mode restriction. Stochastic integration is performed using the weak
  semi-implicit Euler method. We extensively characterize the accuracy of our method,
  finding a faster-than-expected rate of stochastic convergence. Physical consistency
  of the algorithm is demonstrated by considering thermalization of initially random
  states.
publication: '*Physical Review E*'
doi: 10.1103/PhysRevE.89.013302
---
