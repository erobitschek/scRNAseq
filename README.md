# scRNAseq_resources
 Resources for getting started with scRNAseq analysis and the use of particular tools within the realm of scRNAseq analysis

contact: Emily Robitschek (erobitsc@broadinstitute.org, erobitschek@gmail.com)

### Important note: 
This repository is meant to be a resource for getting started with and using some specific tools relevant to scRNAseq analysis. The specifics of each step can and should be modified according to the dataset you are working with (e.g. whether the dataset is from one sample or multiple samples, what datatype you are working with, the format of the input files). 

### Setup 
In order to run these notebooks and reproduce the analyses/use them for your own analyses you will have to install conda and make conda environments compatible with jupyter notebooks and with the right packages.

### Useful links: 
- Cheatsheet for working with conda: https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf
#### Working with conda environments and jupyter notebooks: 
- Getting started with Python environments (using Conda): https://towardsdatascience.com/getting-started-with-python-environments-using-conda-32e9f2779307?gi=8b489a233546
- Manage your Python Virtual Environment with Conda: https://towardsdatascience.com/manage-your-python-virtual-environment-with-conda-a0d2934d5195
- How to Use Jupyter Notebook in 2020: A Beginner’s Tutorial: https://www.dataquest.io/blog/jupyter-notebook-tutorial/
- How to use conda and pip to install packages within Jupyter notebook? https://medium.com/@thabangline/how-to-use-conda-and-pip-to-install-packages-within-jupyter-notebook-d0f2ed23b059
#### Installation instructions for scanpy: 
- https://scanpy.readthedocs.io/en/stable/installation.html

## Description of the different resources currently available in this repository: 

### getting_started_w_scanpy
1. In this folder there is a foundational notebook with some code for running many of the common initial analysis steps for scRNAseq in scanpy. Any of the specific settings for these steps (e.g. normalization, highly variable gene selection) may not be optimal for your dataset and can be modified according to the project.
2. READ THE DOCS! (https://scanpy.readthedocs.io/en/stable/) To find what settings and functions you should apply to your data, keep up to date on the latest best practices in single cell data, and read the scanpy docs.
### infercnv
1. In this folder there is a foundational notebook with some code for running infercnvpy and visualizing some of the results with infercnvpy and scanpy.
2. Should create a virtual environment with scanpy and infercnvpy installed. Some notes on installation of infercnvpy can be found here: https://pypi.org/project/infercnvpy/, can also use the provided yaml file in "setup" folder as the basis for the new environment and execute: 
	<conda env create -f infercnv_env.yml>