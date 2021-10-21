---
layout: post
title: Paper review #1
---

## Paper review #1
### UNIFYING LIKELIHOOD-FREE INFERENCE WITH BLACK-BOX SEQUENCE DESIGN AND BEYOND

[Caution!] I have no deep background on Likelihood-free inference (LFI) and black-box optimization problem at all. Just followed the paper's introduction of them.

### Summary
- New *de novo* biological sequence design algorithm for a limited evaluation process
- Based on black-box optimization formulation
- Performed on TF binding sites, 5' UTR, Antimicrobial peptides, and Fluorescence proteins.
### Introduction and Background
<b>*De novo* biological sequence design is challenging</b> for two reasons: \
(1) the exploration space for sequences is combinatorially large \
(2) sequence usefulness is evaluated via a complicated process which usually involves time-consuming and expensive wet-lab experiments

<b>Likelihood-free inference (LFI)</b> \
LFI refers to a special kind of Bayesian inference setting where the likelihood function is not tractable but sampling (by simulation) from the likelihood is feasible.
While we do not have access to the exact likelihood, we can still simulate (sample) data  from the model simulator. LFI only tries to obtain an approximation of the posterior for the given data.

<b>Biological black-box sequence design</b> \
f(.) is the oracle score function. discover values of m for which f(m) is large. \
In real-world situations, a query of this oracle f could represent a series of wet-lab experiments to measure specific chemical properties or specificity for a given binding site target. In general, these experiments are time- and cost-consuming. As a result, the total number of queries is limited.

<b> Connecting LFI and sequence design </b>


### Method