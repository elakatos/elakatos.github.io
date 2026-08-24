---
layout: page
title: Modelling ultra-sensitive sequencing
img: assets/img/dna_sequencing.jpeg
importance: 3
category: work
---

Cell-free DNA sequencing from blood samples is revolutionising many areas of medicine, from cancer detection to transplant monitoring. These applications require ultra-sensitive detection, so molecular barcoding using unique molecular identifiers (UMIs) has become the standard method for cell-free DNA sequencing. In this method, each DNA molecule is tagged with a UMI, so that following amplification and sequencing, read-outs with the same UMI can be collapsed to (i) correct for sequencing errors and (ii) accurately count the number of original DNA molecules.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/umiseq.jpeg" title="UMIseq" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Current and future interests
Since these techniques are still relatively new, it is not clear if a certain protocol of UMI-based sequencing could be further optimised get maximal read-out, depending on the experimental limitations and goals. 

We work on stochastic models to simulate the UMI-based sequencing protocol and estimate  
(i) the UMI family size distribution   
(ii) the distribution of mutated reads given a certain cancer proportion and cancer cell fraction in the liquid biopsy.

Through these models, we aim to evaluate which experimental set-ups are optimal for mutation/cancer detection and estimate the measurement noise associated with a given experiment - which we can use to improve cfDNA-based cancer monitoring (see Project 2).
