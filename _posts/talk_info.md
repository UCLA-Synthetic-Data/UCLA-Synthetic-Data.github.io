---
layout: post
title: Talk info.
---

Bio:
Ryan McKenna is currently a research scientist at Google AI working at the intersection of federated learning and differential privacy.  He recently graduated with a Ph.D. from the University of Massachusetts Amherst, where he worked with Gerome Miklau and Daniel Sheldon on problems related to differential privacy.  His work spans several broad topics within this field, including linear query answering, local differential privacy, selection, consistency, synthetic data generation, and convex optimization.  To that end, he is interested in designing new tools and mechanisms that are based on sound theoretical principles and work well in practice.  

Title: Marginal-based methods for differentially private synthetic data

Abstract:
In this talk, I will present a general approach for differentially private synthetic data generation known as the select-measure-generate paradigm.  This approach consists of three steps: (1) select a collection of low-dimensional marginal queries, (2) measure those queries privately using a noise-addition mechanism, and (3) generate a synthetic dataset that preserves the noisy measurements well.  In particular, I will present Private-PGM, a general-purpose solution to the generate subproblem that scales effectively to high-dimensional settings by utilizing probabilistic graphical models.  Additionally, I will discuss considerations and principles for the select subproblem, and specific published approaches, including MST, which was used by the winning team in the 2018 NIST DP synthetic data competition, and AIM, which appeared in VLDB 2022 and significantly improves MST.  