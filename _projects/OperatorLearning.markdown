---
layout: page
title: OperatorLearning.jl
description: Deep Learning of operator mappings to solve PDEs in Julia
img: /assets/img/logo.png
importance: 1
category: work
---

In recent years, the scientific computing and machine learning communities have made considerable strides towards each other with a growing amount of shared tools to tackle challenging problems.

This resulted in whats popularly known as Scientific Machine Learning. In this relatively new field, well-established methods from both disciplines are merged in order to decrease the time-to-solution substantially. Oftentimes, prior knowledge of the problem is encoded into deep neural networks with conservation laws that are integrated into the total loss.

A relatively new prospect of this field is the learning of operator mappings. In contrast to Physics Informed Neural Networks (PINN), here the solution of a parametrized set of PDEs is approximated instead of a specific instance given a set of initial and boundary conditions. This enables a much broader applicability for a trained model and has the potential to decrease the solution time compared to classic numerical schemes by multiple orders of magnitude.

For this reason, I decided to create a package in Julia that is capable of handling the most prominent architectures for operator learning. Julia is a programming language that is high-level and close to MATLAB syntax-wise, but offers loads of low-level control and superior performance. The package has become part of the SciML Stack in Julia where most related packages regarding Scientific Machine Learning is developed.

You can follow our work at the [GitHub Package Repo](https://github.com/SciML/OperatorLearning.jl).