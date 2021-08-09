# scRNAseq_resources
 Resources for getting started with scRNAseq analysis and the use of particular tools within the realm of scRNAseq analysis

contact: Emily Robitschek (erobitsc@broadinstitute.org, erobitschek@gmail.com)

### Important note: 
This repository is meant to be a resource for getting started with and using some specific tools relevant to scRNAseq analysis. The specifics of each step can and should be modified according to the dataset you are working with (e.g. whether the dataset is from one sample or multiple samples, what datatype you are working with, the format of the input files). 

### Setup 
In order to run these notebooks and reproduce the analyses/use them for your own analyses you will have to install conda and make conda environments compatible with jupyter notebooks and with the right packages.

## Description of the different resources currently available: 

### getting_started_w_scanpy
1. In this folder there is a foundational notebook with some code for running many of the common initial analysis steps for scRNAseq in scanpy. Any of the specific settings for these steps (e.g. normalization, highly variable gene selection) may not be optimal for your dataset and can be modified according to the project.
2. READ THE DOCS! (https://scanpy.readthedocs.io/en/stable/) To find what settings and functions you should apply to your data, keep up to date on the latest best practices in single cell data, and read the scanpy docs.
### infercnv
1. In this folder there is a foundational notebook with some code for running infercnvpy and visualizing some of the results with infercnvpy and scanpy.