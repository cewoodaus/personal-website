---
title: Quantum Kernel Learning for Bosonic Modes AIP2024
abstract: >-
  Kernel methods are of current interest in quantum machine learning due to
  similarities shared with quantum computing in how information is processed in
  high-dimensional feature (Hilbert) spaces. Kernels are believed to offer
  particular advantages when they are hard to simulate classically, so a kernel
  with the right kind of complexity, or nonclassicality, is considered
  important. Kerr nonlinearities, already a known route to universal continuous
  variable quantum computation, are also a strong source of nonclassicality for
  machine learning. 


  We propose a scheme which implements a kernel on quantum hardware, such as superconducting quantum circuits, and exploits the analogue features of Kerr-coupled modes. The kernel is sampled via displaced parity measurements related to those used in Wigner state tomography. We first focus here on deriving analytically the relevant fiducial state for embedding data, and then on testing the scheme on a common machine learning algorithm---a support vector machine (SVM).

  We discuss the analytical form of the Kerr kernel for two modes, as well as the measurements that would be made via displaced parity operators in a physical system. We use four examples of such measurements, which effectively produce four different Wigner functions each with different labels for the same synthetic data set. We then implement the SVM algorithm using our Kerr kernel, and test its ability to learn each of the four encodings and classify unseen data. We then compare the accuracy of this model to a classical radial basis function SVM. 

  We find that the SVM displays excellent learning with the Kerr kernel, regardless of which displacement operators are used for the labelling, without requiring hyperparameter tuning. 

  The radial basis function, on the other hand, also displays good learning, but requires hyperparameter tuning to approach the benchmarks attained by the Kerr kernel.  
location: AIP2024, Melbourne, Australia
date: 2024-12-03T07:00:24.772Z
date_end: 2023-12-03T07:15:00.000Z
all_day: false
event: Australian Institute of Physics Congress 2024
event_url: https://aipcongress2024.com/
publishDate: 2024-12-07T06:32:24.781Z
draft: false
featured: false
tags:
  - quantum-machine-learning
  - quantum-information
  - quantum-optics
image:
  filename: coherent_splitdata_new_munu1_defaultview.png
  focal_point: Smart
  preview_only: false
---
