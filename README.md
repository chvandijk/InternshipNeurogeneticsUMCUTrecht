# InternshipNeurogeneticsUMCUtrecht

In this repository are some examples of pipelines that I (co)-developed during my internship at the deparment of neurogenetics (UMC Utrecht).

## Final ATAC-seq
This RMarkdown contains the pipeline to run burden analyses on cell-type-specific ATAC-sequencing peaks using whole-genome sequencing variants. 
This pipeline uses the RVAT package.

## FIMO example code
This is a pipeline that I developed to explain to others how the package FIMO is used to find transcription factor binding sites in ATAC-sequencing data. 

## Song_regulatory_network1
This is a pipeline that creates gene regulatory networks from Hi-C-sequencing data and ATAC-sequencing data. It links the peaks of ATAC-sequencing data to genes using the Hi-C data. Thereafter, the regions that map to a genes are tested for association with ALS using burden testing.
