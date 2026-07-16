---
layout: page
title: Tracking cancer evolution from cell-free DNA samples
img: assets/img/cancer_therapy.jpeg
importance: 2
category: work
---

Cell-free DNA (cfDNA) samples offer an unprecedented opportunity to gain a glimpse of tumour composition and evolution without invasive biopsies, which enables frequent sampling in order to real-time follow cancer evolution. However, the inherent heterogeneity and sometimes sub-optimal quality of liquid biopsies mean tracking single nucleotide variants is often not feasible due to high sequencing costs and contamination from healthy DNA.  
One solution is represented by copy number alterations (CNAs), which are typically exclusive to tumour cells and can be reliably detected using low-cost shallow whole-genome sequencing even in low quality (e.g. archival) or low tumour content (e.g. cfDNA) materials.  



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/liquidcna.png" title="liquidcna" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Previous work
- Developed liquidCNA, a method for tracking the size of an emerging subclone from cfDNA samples without any prior knowledge of the genomic identity of the clone. (See illustration above.)
- Quantified the proportion of (potentially) resistant subclone in ovarian cancer samples monitored through therapy.
- Developed BayesCNA, a segmentation and copy number quantification algorithm based on Bayesian changepoint detection. BayesCNA is particularly suitable for low-tumour content low-coverage sequencing samples.

### Current and future interests
Ultimately, we are interested in applying our methods to parametrise mechanistic models of on-treatment tumour dynamics. To this aim, we improving on liquidCNA and BayesCNA to make quantative predictions available for a wider set of samples. 
- Improving tumour DNA detection within cfDNA samples by developing filters to improve tumour content in sequencing data.
- Improving CNA segmentation and quantification by using joint analysis of samples from the same patient.
- Developing a pipeline to inform mechanistic models of tumour growth from longitudinal CNA data.
- Creating digital twins/ virtual cohorts of patients informed from monitoring cfDNA data collected through personalised panels. We then want to use these cohorts to run in silico tests of alternative treatment protocols.
- Investigating the optimal timing of cfDNA sample collection for parametrising mechanistic models.

