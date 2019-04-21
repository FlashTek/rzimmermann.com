---
title: "Predicting and Observing Chaotic Dynamics in Excitable Media Using Machine Learning"
type: poster
collection: publications
permalink: /publication/2018-09-23-chaotic-dynamics
excerpt: 'Analysis of chaotic dynamics using sequential and recurrent neural networks and classical Machine Learning methods.'
date: 2018-09-24
authors: 'Parlitz, U. and **Zimmermann, R. S.** , Herzog, S. and Isenseee, J. and Datseris, G.'
venue: 'CinC'
citation: 'Parlitz, U. and Zimmermann, R. S. , Herzog, S. and Isenseee, J. and Datseris, G. (2018). Predicting and Observing Chaotic Dynamics in Excitable Media Using Machine Learning. CinC 2018, Maastrich.'
---

Cardiac arrhythmias like ventricular fibrillation are governed by spatio-temporal dynamics of electro-mechanical activity in the heart muscle. In general, only some of the physical variables describing these processes can be measured directly (e.g., membrane voltages or mechanical deformation). To still obtain a complete set of state variables an observer based on a mathematical model may be employed for reconstructing dynamical variables from available time series. This approach constitutes the core of any data assimilation scheme and it is usually implemented by incorporating the model equations into the algorithm. As an alternative, machine learning methods can be applied to approximate the functional relation between observed time series and (unknown) state variables. We present a dynamical observer for two dimensional PDE models describing excitable media, where the required cross prediction from observed time series to not measured state variables is provided by Echo State Networks receiving input from local regions in space, only [1]. The efficacy of this approach is demonstrated for (noisy) data from a (cubic) Barkley model and the Bueno-Orovio-Cherry-Fenton model describing chaotic electrical wave propagation in cardiac tissue. This kind of learning observer can also be trained with experimental data, where during an extended measurement not only the observed time series but also other dynamical variables of interest are measured.

[1] Zimmermann, R. S. and Parlitz, U. Chaos (2018)