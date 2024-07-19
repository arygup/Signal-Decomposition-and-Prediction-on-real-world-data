# EWNETs and Signal Decomposition

**Authors:**  Aryan Gupta, Amey Choudhary, Keshav Gupta

**Instructor:** Dr. Chittaranjan Hens

**Date:** April 21, 2024

## Abstract

In our project, we aim to understand the novel approach for forecasting epidemics, EWNETs, as proposed in Epicasting: An Ensemble Wavelet Neural Network for forecasting epidemics (2023). We reproduce the same and analyze the results for it. We also experiment with other methods for signal decomposition and provide a comparative report for them.

[Link to the paper](https://www.sciencedirect.com/science/article/pii/S0893608023002939)

## Table of Contents

1. [Abstract](#abstract)
2. [Understanding of the Paper](#understanding-of-the-paper)
   - [Current methods for epidemic forecasting](#current-methods-for-epidemic-forecasting)
   - [Explaining EWNETs](#explaining-ewnets)
     - [MODWT approach](#modwt-approach)
     - [EWNET model architecture](#ewnet-model-architecture)
     - [EWNET model working](#ewnet-model-working)
3. [Experimentation results of EWNETs on datasets](#experimentation-results-of-ewnets-on-datasets)
4. [Implementing our own EWNET](#implementing-our-own-ewnet)
5. [Using other Signal Decomposition Methods](#using-other-signal-decomposition-methods)
   - [Seasonal and Trend decomposition using Loess (STL)](#seasonal-and-trend-decomposition-using-loess-stl)
   - [Singular Spectral Analysis (SSA)](#singular-spectral-analysis-ssa)
   - [Empirical Mode Decomposition (EMD)](#empirical-mode-decomposition-emd)
   - [Hilbert Huang Transform (HHT)](#hilbert-huang-transform-hht)
   - [Empirical Wavelet Transform (EWT)](#empirical-wavelet-transform-ewt)
6. [Experimentation Results](#experimentation-results)
   - [MODWT](#modwt)
   - [STL](#stl)
   - [SSA](#ssa)
   - [EMD](#emd)
   - [HHT](#hht)
   - [EWT](#ewt)
7. [Discussion and Conclusion](#discussion-and-conclusion)



# Kindly Continue Reading :
https://github.com/arygup/Signal-Decomposition-and-Prediction-on-real-world-data/blob/main/DPCN%202024%20Report.pdf
